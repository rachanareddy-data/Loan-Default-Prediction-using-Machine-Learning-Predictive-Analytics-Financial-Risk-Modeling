# 💰 Loan Default Prediction using Machine Learning

## 📌 Overview
This project builds a predictive analytics model to identify loan default risk using real-world Lending Club dataset. The goal is to help financial institutions assess borrower risk and improve lending decisions using machine learning.

---

## 🎯 Objective
- Predict whether a borrower will default (bad_payer)
- Handle class imbalance using SMOTE
- Build a high-performance classification model for financial risk prediction

---

## 📊 Dataset
- Source: Lending Club dataset
- Records: 200,000+ loans
- Features: Loan amount, interest rate, income, employment history, credit grade, etc.
- Target: `bad_payer` (0 = Non-default, 1 = Default)

---

## ⚙️ Data Preprocessing
- Selected key financial features
- Removed missing and invalid values
- One-hot encoding for categorical variables
- Converted all features to numeric format
- Applied SMOTE for class imbalance handling

---

## 🤖 Machine Learning Model
- Algorithm: Random Forest Classifier
- Class balancing: SMOTE + class_weight
- Train/Test Split: 80/20

---

## 📈 Model Performance

- Accuracy: **88.36%**
- Default Class Recall: **81%**
- Non-default Recall: **95%**

### Key Insight:
Model successfully identifies high-risk borrowers while maintaining strong overall accuracy.

---

## 📊 Evaluation Metrics
- Accuracy Score
- Precision / Recall / F1-score
- Confusion Matrix

---

## 🧠 Key Insights
- Income and debt-to-income ratio are strong predictors of default risk
- SMOTE significantly improved minority class detection
- Random Forest performed well on high-dimensional financial data

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Seaborn, Matplotlib

---

## 🚀 Business Impact
This model can help:
- Banks reduce loan defaults
- Improve credit risk assessment
- Optimize lending decisions
- Reduce financial losses

---

## 👩‍💻 Author
Rachana Baddam  
M.S. Data Science – Saint Peter’s University  
GitHub: https://github.com/rachanareddy-data
