# Predicting Loan Payback

## 📌 Project Overview

[Competion Link](https://www.kaggle.com/competitions/playground-series-s5e11/data)

The goal of this project is to **predict the probability that a borrower will pay back their loan**.  
This is a binary classification problem where:

- **Target Variable:** `loan_paid` (1 = paid back, 0 = default)
- **Output:** Predicted **probability** of loan repayment  
- **Evaluation Metric:** **Area Under the ROC Curve (AUC-ROC)**

A higher AUC score indicates better model performance in distinguishing between borrowers who pay back their loans and those who default.

---

## 🧹 Data Preprocessing
Steps performed in this project:

1. Handle missing values  
2. Encode categorical variables  
3. Scale or normalize numerical features  
4. Train-test split  
5. Handle class imbalance (SMOTE or class weights)

---

## 🤖 Modeling
Different machine learning models can be used:

- Logistic Regression  
- Random Forest  
- XGBoost / LightGBM / CatBoost  
- Neural Networks  

Each model outputs a **probability** between 0 and 1 representing likelihood of repayment.

---

## 📈 Evaluation Metric: ROC-AUC
Submissions are judged based on:

### **ROC-AUC Score**

- Measures model's ability to rank borrowers correctly  
- Works well with imbalanced datasets  
- Uses probability predictions instead of class labels  

Higher AUC = Better performance.

---


