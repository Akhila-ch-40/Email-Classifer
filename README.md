# Email-Classifer
# Smart Email Classifier Dataset

This repository includes a synthetic email classification dataset: **sample_email_dataset_600.csv**

## 📄 Dataset Overview

- **File:** `sample_email_dataset_600.csv`
- **Size:** 600 rows
- **Format:** CSV
- **Columns:**
  - `email`: Text content of the email
  - `label`: Classification label for the email (`spam` or `ham`)

### 📊 Sample Entries

| email                                | label |
|--------------------------------------|-------|
| Win a free iPhone now!               | spam  |
| Meeting at 10 AM                     | ham   |
| Buy now and save 50%                 | spam  |
| Please review the attached document  | ham   |

## 🧠 Usage

This dataset can be used to train and evaluate machine learning models for **binary text classification** (spam detection).

### Example Use Case in Python

```python
import pandas as pd

# Load the dataset
df = pd.read_csv("sample_email_dataset_600.csv")

# Preview data
print(df.head())

# Access labels
emails = df['email']
labels = df['label']
```

## 📌 Notes

- The dataset is **synthetic** and created for educational/demo purposes.
- You can expand this dataset or replace it with real-world data like Enron or UCI Spambase for production-level projects.

## ✅ Ideal For

- Email spam classifiers
- NLP preprocessing demos
- TF-IDF and Naive Bayes/SVM pipelines
- Google Colab and VS Code training sessions

---

Created for use in the Smart Email Classifier project.
