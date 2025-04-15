# Loan Repayment Prediction

This project predicts whether a borrower will fully repay a loan using supervised machine learning models. It helps identify high-risk borrowers and supports smarter lending decisions.

## 📄 Dataset Description

The dataset contains information about individual loans and borrower attributes:

| Field           | Description                                                                 |
|---------------- |-----------------------------------------------------------------------------|
| Loan_status     | Whether a loan is paid off or in collection                                 |
| Principal       | Basic principal loan amount                                                 |
| Terms           | Origination terms: weekly, biweekly, or monthly payoff schedule             |
| Effective_date  | The date when the loan was originated                                       |
| Due_date        | One-time payoff due date for the loan                                       |
| Age             | Age of the applicant                                                        |
| Education       | Education level of the applicant                                            |
| Gender          | Gender of the applicant                                                     |

## 🔍 Project Overview

The goal is to build machine learning models that can accurately predict loan repayment outcomes based on borrower data.

## 🧠 Models Used

- Decision Tree ✅ (Best performance)
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Logistic Regression

## 📊 Evaluation Metrics

- Jaccard Index
- F1-Score
- Log Loss (for Logistic Regression)

Among all models, the **Decision Tree Classifier** delivered the best performance across most metrics.

## 🛠️ Technologies

- Python
- Scikit-Learn
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook
