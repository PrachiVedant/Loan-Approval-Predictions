# 📊 Loan Prediction Using Machine Learning

This project is a machine learning-based solution to predict the likelihood of a loan being approved based on customer data. It uses Python and popular libraries like Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn to preprocess the data, visualize patterns, train classification models, and evaluate their performance.

---

## 🔍 Problem Statement

Given customer demographics and financial information, the goal is to predict whether a customer's loan application will be approved.

---

## 📁 Dataset

The dataset used for this project includes features such as:

- Gender  
- Married  
- Dependents  
- Education  
- Self_Employed  
- ApplicantIncome  
- CoapplicantIncome  
- LoanAmount  
- Loan_Amount_Term  
- Credit_History  
- Property_Area  
- Loan_Status (Target)

The data was processed to handle missing values, convert categorical variables into numerical values, and normalize the features.

---

## ⚙️ Models Used

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  
- XGBoost  

Each model is trained and evaluated using accuracy scores.

---

## 📈 Evaluation

The models were evaluated using classification metrics. Random Forest and XGBoost performed best in terms of accuracy.

---

## 📌 Requirements

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
