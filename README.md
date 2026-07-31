📩 Spam SMS Classification using Logistic Regression

A complete Machine Learning classification project for detecting spam messages using the SMS Spam Collection Dataset. This project covers the entire ML workflow, from data exploration and feature engineering to model evaluation and hyperparameter tuning.

⭐ Project Highlights

* ✅ Complete end-to-end Machine Learning workflow
* ✅ Data Cleaning & Duplicate Handling
* ✅ Exploratory Data Analysis (EDA)
* ✅ Text-based Feature Engineering
* ✅ Text Preprocessing & TF-IDF Vectorization
* ✅ Logistic Regression Classification
* ✅ Hyperparameter Tuning with GridSearchCV with 5-Fold Cross Validation
* ✅ Comprehensive Model Evaluation
* ✅ Confusion Matrix & Classification Report Visualization

📌 Project Overview
The objective of this project is to build a machine learning model capable of classifying SMS messages as spam or legitimate (ham) based on their text content.
The project follows a complete machine learning pipeline including:

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Duplicate Removal
* Feature Engineering
* Text Preprocessing
* TF-IDF Vectorization
* Model Training
* Hyperparameter Tuning
* Model Evaluation

📊 Dataset
Dataset: SMS Spam Collection Dataset
Each record contains:

* Label — the message category
* Message — the raw SMS text

Target Variable:

* Label
   * ham → Legitimate Message
   * spam → Spam Message

🛠 Data Preprocessing
The following preprocessing steps were performed:

* Checked dataset structure and descriptive statistics
* Identified duplicate records
* Removed 403 duplicate rows before splitting the data
* Verified no missing values were present
* Converted all message text to lowercase
* Split data into training and test sets (80/20)
* Vectorized text using TF-IDF (fit on training data only)

📈 Exploratory Data Analysis
EDA includes:

* Class distribution (ham vs. spam)
* Engineered text-based features:
   * Message Length
   * Word Count
   * Exclamation Mark Count
   * Digit Count
   * URL Presence
* Feature distributions by class (histograms & boxplots)

These visualizations help understand how spam messages differ structurally from legitimate messages.

🤖 Machine Learning Model
Algorithm

* Logistic Regression

Model selection process:

* TF-IDF feature extraction from message text
* Hyperparameter tuning using GridSearchCV
* Grid search over regularization strength (C) and solver
* 5-Fold Cross Validation, optimized for F1-score

📊 Model Evaluation
The model was evaluated using multiple classification metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Jaccard Index
* Log Loss
* Confusion Matrix
* Classification Report

This provides a comprehensive evaluation rather than relying only on accuracy — an important consideration given the imbalanced nature of spam datasets.

📈 Final Performance
Best Hyperparameters

* C: 100.0
* Solver: lbfgs

Test Accuracy

* 98%

Additional evaluation metrics:

* F1-Score: 0.94
* Jaccard Index: 0.89
* Precision & Recall (spam class): 0.96 / 0.92
* Confusion Matrix
* Classification Report

📚 Libraries Used

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn

⚙️ Installation
Clone the repository:

```
git clone git@github.com:MohammadNasrollahiCE/Email-Spam-Classification.git
cd Spam-Classification-LogisticRegression
```

Install the required packages:

```
pip install -r requirements.txt
```

Run the Jupyter Notebook:

```
jupyter notebook
```

📂 Project Structure

```
Spam-Classification-LogisticRegression/
│
├── Spam-Email-Classifier-LogReg.ipynb
├── README.md
├── requirements.txt
│
└── dataset/
    └── SMSSpamCollection

```

🚀 Key Concepts Demonstrated

* Binary Classification
* Data Cleaning
* Duplicate Removal
* Text-based Feature Engineering
* Exploratory Data Analysis
* Text Preprocessing
* TF-IDF Vectorization
* Logistic Regression Classification
* Hyperparameter Tuning
* GridSearchCV
* Cross Validation
* Model Evaluation

📖 Learning Objectives
This project demonstrates a complete machine learning classification workflow and serves as a practical example of building, tuning, and evaluating a text classification model using Scikit-Learn.

👨‍💻 Author
Mohammad Nasrollahi 'Arad'
Computer Engineering Student
Interested in:

* Machine Learning
* Data Science
* Artificial Intelligence

GitHub: https://github.com/MohammadNasrollahiCE

