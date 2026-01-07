# Credit Risk ML – Loan Default Prediction

## Overview
This project predicts whether a loan applicant is likely to default using a **Logistic Regression** model.  

It demonstrates a complete **end-to-end machine learning workflow** including data loading, preprocessing, EDA, model training, and evaluation.

Logistic Regression was chosen because it provides interpretable coefficients, which is important in financial risk modeling where explainability matters.


## Dataset
The dataset contains customer loan application details such as:
- Gender
- Marital status
- Education
- Employment status
- Applicant income
- Loan amount
- Credit history

Target variable:
- `Loan_Default` (1 = Default, 0 = No Default)

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## ML Workflow
1. Data Loading & Inspection  
2. Exploratory Data Analysis (EDA)  
3. Data Preprocessing  
4. Train-Test Split  
5. Logistic Regression Model Training  
6. Model Evaluation (Accuracy, Confusion Matrix)

## Results

The Logistic Regression model achieved an overall accuracy of **96%** on the test dataset.

- **Accuracy:** 96%
- **Precision (weighted):** 96%
- **Recall (weighted):** 96%
- **F1-score (weighted):** 96%

The model performs consistently across both classes, indicating good generalization.


This indicates that the model is highly effective at identifying defaulters while maintaining a low false positive rate.


