# Loan Default Prediction Using Machine Learning

## Project Overview

Loan default prediction is one of the most important applications of machine learning in the financial industry. This project develops and evaluates multiple supervised machine learning models to predict whether a borrower is likely to default on a loan using demographic, financial, and property-related information.

The goal is to assist financial institutions in identifying high-risk borrowers and improving credit risk assessment.

---

## Problem Statement

Financial institutions face significant losses due to loan defaults. Early identification of high-risk applicants enables lenders to make informed lending decisions, reduce financial risk, and improve portfolio quality.

The objective of this project is to build an accurate classification model capable of predicting loan defaults before loan approval.

---

## Dataset

- **Domain:** Banking & Finance
- **Dataset Type:** Loan Applicant Records
- **Target Variable:** `Status`

The dataset contains borrower demographic, financial, credit, and property-related attributes used for predicting loan default.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## Project Workflow

- Data Collection
- Data Understanding
- Feature Selection
- Data Cleaning
- Missing Value Treatment
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Model Training
- Model Evaluation
- Cross Validation
- Model Comparison

---

## Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Logistic Regression (Scaled)
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

---

## Model Performance

| Model | Accuracy | ROC-AUC |
|-------|---------:|---------:|
| Logistic Regression | 75.3% | 0.500 |
| Logistic Regression (Scaled) | 75.3% | 0.500 |
| Decision Tree | 90.9% | 0.891 |
| Random Forest | 91.3% | 0.867 |
| **XGBoost** | **92.2%** | **0.908** |

---

## Key Results

- Achieved **92.2% accuracy** using XGBoost.
- Achieved **0.908 ROC-AUC**, demonstrating strong class discrimination.
- Tree-based models significantly outperformed Logistic Regression.
- Performed **10-fold Cross Validation** to evaluate model generalization.

---

## Business Impact

This predictive model can help financial institutions:

- Identify high-risk borrowers before loan approval.
- Reduce loan default rates.
- Improve credit risk assessment.
- Support data-driven lending decisions.
