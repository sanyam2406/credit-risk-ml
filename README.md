# Credit Risk ML – Loan Default Prediction

## Overview
This project predicts whether a loan applicant is likely to default using a **Logistic Regression** model. It demonstrates an end-to-end machine learning workflow commonly used in **financial risk modeling**, including data preprocessing, model training, and evaluation.

---

## Problem Statement
Loan default prediction is a critical task for financial institutions.  
The objective of this project is to classify loan applicants as **defaulters** or **non-defaulters** based on historical loan application data.

---

## Dataset
The dataset contains loan applicant information such as:

- Gender  
- Marital status  
- Education  
- Employment status  
- Applicant income  
- Loan amount  
- Credit history  

### Target Variable
- `Loan_Default`  
  - `1` → Default  
  - `0` → No default  

---

## Modeling Approach
- **Algorithm:** Logistic Regression  
- **Rationale:** Logistic Regression is widely used in credit risk modeling due to its simplicity, interpretability, and effectiveness for binary classification problems.

The dataset is split into training and test sets to evaluate model performance on unseen data.

---

## Model Performance
The Logistic Regression model was evaluated on a held-out test dataset.

- **Accuracy:** 96%  
- **Precision (weighted average):** 96%  
- **Recall (weighted average):** 96%  
- **F1-score (weighted average):** 96%  

### Loan Default Class (Positive Class)
- **Precision:** 97%  
- **Recall:** 97%  

These results indicate strong predictive performance with consistent classification across both classes.

---

## Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## How to Run

```bash
git clone https://github.com/sanyam2406/credit-risk-ml.git
cd credit-risk-ml
pip install pandas numpy scikit-learn


