# 📧 Spam Email Classification using Logistic Regression

> A complete end-to-end Machine Learning project for SMS spam detection using TF-IDF vectorization and Logistic Regression.

---

## 📖 Overview

This project builds a complete Machine Learning pipeline capable of classifying SMS messages as **Spam** or **Ham**.

The project covers every major stage of a real-world ML workflow:

- Data Cleaning
- Duplicate Removal
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Text Preprocessing
- TF-IDF Vectorization
- Model Training
- Hyperparameter Tuning
- Performance Evaluation

Instead of focusing only on achieving high accuracy, the project emphasizes **building a clean, reproducible, and trustworthy machine learning pipeline**.

---

## ✨ Features

✔ Duplicate Detection & Removal

✔ Missing Value Check

✔ Exploratory Data Analysis

✔ Text Feature Engineering

✔ TF-IDF Vectorization

✔ Logistic Regression Classifier

✔ GridSearchCV Hyperparameter Tuning

✔ Cross Validation

✔ Evaluation using multiple metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Jaccard Index
- Log Loss
- Confusion Matrix
- Classification Report

---

## 📂 Dataset

Dataset:

SMS Spam Collection Dataset

Original samples:

**5,572**

After removing duplicates:

**5,169**

Classes:

- Ham
- Spam

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

# 📊 Exploratory Data Analysis

Several statistical features were extracted to better understand the dataset.

Examples include:

- Message Length
- Word Count
- Exclamation Count
- Digit Count
- URL Presence

EDA showed that spam messages generally:

- are longer
- contain more digits
- contain more exclamation marks
- include URLs more frequently

---

# ⚙️ Text Preprocessing

The preprocessing pipeline consists of:

- Lowercasing
- Train/Test Split
- TF-IDF Vectorization

The final model was trained using TF-IDF features only.

---

# 🤖 Model

Classifier:

**Logistic Regression**

Hyperparameter tuning was performed using **GridSearchCV** with **5-Fold Cross Validation**.

Best Parameters:

```
C = 100
solver = lbfgs
```

Best Cross Validation F1 Score:

```
≈ 0.94
```

    --

# 📈 Results

| Metric | Score |
|---------|------:|
| Accuracy | 0.98 |
| Precision | 0.96 |
| Recall | 0.92 |
| F1 Score | 0.94 |
| Jaccard Index | 0.89 |

---

# 📊 Confusion Matrix

| | Predicted Ham | Predicted Spam |
|---|---:|---:|
| Actual Ham | 889 | 5 |
| Actual Spam | 11 | 129 |

---

# 📁 Project Structure

```
Spam-Email-Classifier/
│
├── Spam-Email-Classifier-LogReg.ipynb
├── spam.csv
└── README.md
```

---

# 🚀 How to Run

```bash
git clone https://github.com/yourusername/Spam-Email-Classifier.git

cd Spam-Email-Classifier

pip install -r requirements.txt

jupyter notebook
```

Run the notebook step-by-step.

---

# 📌 Future Improvements

- Pipeline API
- Model Persistence with Joblib
- Compare with Naive Bayes
- Compare with Linear SVM
- Use ColumnTransformer
- Deploy using Streamlit
- REST API using FastAPI

---

# 👨‍💻 Author

**Mohammad Nasrollahi**

Computer Engineering Student

Machine Learning Enthusiast

GitHub:
https://github.com/yourusername

LinkedIn:
https://linkedin.com/in/yourprofile

---

## ⭐ If you found this project useful, consider giving it a star!
