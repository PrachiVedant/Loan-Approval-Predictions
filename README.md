# 💼 Loan Prediction Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

A complete machine learning project that predicts whether a loan will be approved based on customer details. It includes data preprocessing, visualization, model training, evaluation, and comparison using multiple classification algorithms.

---

## 📌 Table of Contents

- [📌 Table of Contents](#-table-of-contents)
- [📍 Project Overview](#-project-overview)
- [🧠 Algorithms Used](#-algorithms-used)
- [📁 Dataset Description](#-dataset-description)
- [📊 Exploratory Data Analysis](#-exploratory-data-analysis)
- [⚙️ Installation](#️-installation)
- [▶️ How to Run](#️-how-to-run)
- [🌐 Google Colab Access](#-google-colab-access)
- [📈 Model Evaluation](#-model-evaluation)
- [📎 Project Structure](#-project-structure)
- [📚 Requirements](#-requirements)
- [🧑‍💻 Author](#-author)
- [📄 License](#-license)

---

## 📍 Project Overview

This project aims to build a predictive model that determines whether a customer's loan application will be approved or not. It walks through the entire ML pipeline:

- Data cleaning and preprocessing
- Feature engineering
- Data visualization
- Model building with multiple classifiers
- Evaluation and comparison of results

---

## 🧠 Algorithms Used

The following machine learning algorithms are implemented and compared:

- ✅ Logistic Regression  
- ✅ K-Nearest Neighbors (KNN)  
- ✅ Decision Tree  
- ✅ Random Forest  
- ✅ XGBoost  

---

## 📁 Dataset Description

The dataset contains customer information with the following columns:

| Feature            | Description                        |
|--------------------|------------------------------------|
| Gender             | Male/Female                        |
| Married            | Marital status                     |
| Dependents         | Number of dependents               |
| Education          | Graduate/Not Graduate              |
| Self_Employed      | Yes/No                             |
| ApplicantIncome    | Income of the applicant            |
| CoapplicantIncome  | Income of the coapplicant          |
| LoanAmount         | Loan amount requested              |
| Loan_Amount_Term   | Duration of loan in months         |
| Credit_History     | 1: Yes, 0: No                      |
| Property_Area      | Urban/Semiurban/Rural              |
| Loan_Status        | Y (Yes) / N (No) — Target Variable |

---

## 📊 Exploratory Data Analysis

- Missing values handled
- Distributions visualized using histograms, count plots, box plots
- Categorical variables encoded
- Correlation matrix for feature insights

---

## ⚙️ Installation

Make sure Python 3.8+ is installed. Then install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
````

Or install via requirements file (if included):

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

### 💻 Run Locally

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/loan-prediction.git
cd loan-prediction
```

2. **Launch Jupyter Notebook**

```bash
jupyter notebook loan.ipynb
```

3. **Execute All Cells**

* Follow each step in the notebook from data loading to final model evaluation.

---

## 🌐 Google Colab Access

Don’t want to run locally? Open the notebook in Google Colab with a single click:

👉 [**Run on Colab**](https://colab.research.google.com/drive/12cKCfoyo5Cidp_NXlLIP3HEWm1-t6WvK?usp=sharing)

---

## 📈 Model Evaluation

Each model is evaluated based on **accuracy**. Final comparison helps identify the most effective model for loan approval prediction.

---

## 📎 Project Structure

```
loan-prediction/
│
├── loan.ipynb              # Main notebook with all ML steps
├── README.md               # Project overview (you are here)
├── requirements.txt        # Python dependencies (optional)
└── dataset/                # Folder for dataset (if applicable)
```

---

## 📚 Requirements

* Python 3.8+
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* xgboost
* jupyter (for local runs)

---

## 🧑‍💻 Author

**Prachi Bhavesh Vedant**
AI & Data Science Student | Passionate about Machine Learning & Real-World Applications

---

## 📄 License

This project is licensed under the MIT License. Feel free to use and adapt it for learning or commercial purposes.

---

⭐️ *If you like this project, consider giving it a star!*

```
