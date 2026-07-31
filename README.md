<div align="center">

# 📩 Spam SMS Classification using Logistic Regression

**A complete end-to-end Machine Learning project for classifying SMS messages using TF-IDF Vectorization and Logistic Regression.**

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

---

# 📚 Table of Contents

- [⭐ Project Highlights](#-project-highlights)
- [📌 Project Overview](#-project-overview)
- [📊 Dataset](#-dataset)
- [🛠 Data Preprocessing](#-data-preprocessing)
- [📈 Exploratory Data Analysis](#-exploratory-data-analysis)
- [🤖 Machine Learning Model](#-machine-learning-model)
- [📊 Model Evaluation](#-model-evaluation)
- [🎯 Final Performance](#-final-performance)
- [🔄 Project Workflow](#-project-workflow)
- [📚 Libraries Used](#-libraries-used)
- [⚙️ Installation](#️-installation)
- [📂 Project Structure](#-project-structure)
- [🚀 Key Concepts Demonstrated](#-key-concepts-demonstrated)
- [📖 Learning Objectives](#-learning-objectives)
- [👨‍💻 Author](#-author)

---

# ⭐ Project Highlights

- ✅ Complete end-to-end Machine Learning workflow
- ✅ Data Cleaning & Duplicate Handling
- ✅ Exploratory Data Analysis (EDA)
- ✅ Text-based Feature Engineering
- ✅ Text Preprocessing & TF-IDF Vectorization
- ✅ Logistic Regression Classification
- ✅ GridSearchCV with 5-Fold Cross Validation
- ✅ Comprehensive Model Evaluation
- ✅ Confusion Matrix & Classification Report

---

# 📌 Project Overview

The objective of this project is to build a Machine Learning model capable of classifying SMS messages as **Spam** or **Ham** based on their textual content.

The project follows a complete ML pipeline including:

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Duplicate Removal
- Feature Engineering
- Text Preprocessing
- TF-IDF Vectorization
- Model Training
- Hyperparameter Tuning
- Model Evaluation

---

# 📊 Dataset

**Dataset:** SMS Spam Collection Dataset

Each record contains:

- **Label** — Message Category
- **Message** — Raw SMS Text

### Target Variable

| Label | Description |
|------|-------------|
| Ham | Legitimate Message |
| Spam | Spam Message |

---

# 🛠 Data Preprocessing

The following preprocessing steps were performed:

- Checked dataset structure and descriptive statistics
- Identified duplicate records
- Removed **403 duplicate rows**
- Verified no missing values
- Converted messages to lowercase
- Split dataset into **80% Train / 20% Test**
- Applied **TF-IDF Vectorization** (fit only on training data)

---

# 📈 Exploratory Data Analysis

EDA includes:

- Class Distribution
- Message Length
- Word Count
- Exclamation Count
- Digit Count
- URL Presence
- Histograms
- Boxplots

These analyses provide insight into the structural differences between spam and legitimate messages.

---

# 🤖 Machine Learning Model

### Algorithm

**Logistic Regression**

### Model Selection

- TF-IDF Feature Extraction
- GridSearchCV
- Hyperparameter Tuning
- 5-Fold Cross Validation
- Optimization based on **F1-Score**

---

# 📊 Model Evaluation

The model was evaluated using multiple metrics:

| Metric |
|---------|
| Accuracy |
| Precision |
| Recall |
| F1-Score |
| Jaccard Index |
| Log Loss |
| Confusion Matrix |
| Classification Report |

This provides a more reliable evaluation than relying solely on accuracy.

---

# 🎯 Final Performance

### Best Hyperparameters

| Parameter | Value |
|----------|------:|
| C | **100** |
| Solver | **lbfgs** |

### Test Performance

| Metric | Score |
|---------|------:|
| Accuracy | **98%** |
| Precision | **0.96** |
| Recall | **0.92** |
| F1-Score | **0.94** |
| Jaccard Index | **0.89** |

---

# 🔄 Project Workflow

```text
SMS Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Duplicate Removal
      │
      ▼
EDA
      │
      ▼
Feature Engineering
      │
      ▼
Text Preprocessing
      │
      ▼
TF-IDF Vectorization
      │
      ▼
GridSearchCV
      │
      ▼
Logistic Regression
      │
      ▼
Model Evaluation
```

---

# 📚 Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

# ⚙️ Installation

Clone the repository

```bash
git clone git@github.com:MohammadNasrollahiCE/Email-Spam-Classification.git

cd Spam-Classification-LogisticRegression
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

# 📂 Project Structure

```text
Spam-Classification-LogisticRegression/
│
├── Spam-Email-Classifier-LogReg.ipynb
├── README.md
├── requirements.txt
│
└── dataset/
    └── SMSSpamCollection
```

---

# 🚀 Key Concepts Demonstrated

| Concept | Status |
|---------|:------:|
| Binary Classification | ✅ |
| Data Cleaning | ✅ |
| Duplicate Removal | ✅ |
| Feature Engineering | ✅ |
| Text Preprocessing | ✅ |
| TF-IDF Vectorization | ✅ |
| Logistic Regression | ✅ |
| Hyperparameter Tuning | ✅ |
| GridSearchCV | ✅ |
| Cross Validation | ✅ |
| Model Evaluation | ✅ |

---

# 📖 Learning Objectives

This project demonstrates a complete Machine Learning classification workflow and serves as a practical example of building, tuning, and evaluating a text classification model using **Scikit-Learn**.

---

# 👨‍💻 Author

**Mohammad Nasrollahi (Arad)**

Computer Engineering Student

### Interests

- Machine Learning
- Data Science
- Artificial Intelligence

**GitHub**

https://github.com/MohammadNasrollahiCE

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a Star!

</div>
