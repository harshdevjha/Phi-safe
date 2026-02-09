# Phi-safe

Phi-safe is a machine learning–based system designed to detect
phishing or compromised cryptocurrency wallets using
transaction-level behavioral features.

## 📌 Project Overview
Cryptocurrency wallets involved in phishing or malicious activities
often exhibit abnormal transaction patterns.  
This project analyzes such patterns and applies machine learning
techniques to classify wallets as **legitimate** or **compromised**.

## 🎯 Objective
To build a binary classification model that identifies:
- 0 → Legitimate wallet
- 1 → Phishing / Compromised wallet

## 🧠 Models Implemented
- Random Forest
- Support Vector Machine (SVM)
- Logistic Regression
- XGBoost

## ⚙️ Methodology
1. Data cleaning and preprocessing
2. Feature selection using Mutual Information
3. Removal of low-variance, highly correlated, and sparse features
4. Handling class imbalance using SMOTE
5. Feature scaling (where applicable)
6. Model training, evaluation, and comparison

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Cross-validation accuracy

## 🏆 Key Results
Random Forest achieved the best overall performance with high accuracy
and recall, making it suitable for detecting compromised wallets.

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Imbalanced-learn
- Matplotlib, Seaborn

## 🚀 How to Run
1. Clone the repository
2. Install required dependencies
3. Run the notebook `train_wallet_model2.ipynb`

## 📌 Disclaimer
This project is intended for academic and research purposes only.
