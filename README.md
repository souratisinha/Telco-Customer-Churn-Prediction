# Telco Customer Churn Prediction

## Project Overview
A Predictive Analytics project in the Marketing domain that predicts customer churn 
for a telecom company using machine learning classification models.

## Business Problem
Customer churn costs telecom companies billions annually. This project builds 
predictive models to identify at-risk customers so the marketing team can launch 
targeted retention campaigns before customers leave.

## Dataset
- **Source:** Kaggle — Telco Customer Churn
- **Records:** 7,043 customers (7,021 after cleaning)
- **Features:** 21 columns (demographics, services, account info, charges)
- **Target Variable:** Churn (Yes/No)
- **Class Distribution:** 73.5% Not Churned, 26.5% Churned

## Models Built
1. **Logistic Regression** — Linear classifier with sigmoid function
2. **Decision Tree** — Rule-based interpretable classifier
3. **Random Forest** — Ensemble of 100 decision trees
4. **K-Nearest Neighbors (KNN)** — Distance-based classifier

## Model Comparison Leaderboard

| Rank | Model               | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|------|---------------------|----------|-----------|--------|----------|---------|
| 1    | Logistic Regression | 0.7431   | 0.5096    | 0.7876 | 0.6188   | 0.8385  |
| 2    | Random Forest       | 0.7772   | 0.5660    | 0.6801 | 0.6178   | 0.8361  |
| 3    | Decision Tree       | 0.7601   | 0.5349    | 0.7204 | 0.6140   | 0.8218  |
| 4    | KNN                 | 0.7559   | 0.5443    | 0.4785 | 0.5093   | 0.7636  |

## Best Model
**Logistic Regression** with ROC-AUC of 0.8385 and Recall of 0.7876

## Key Findings
- Month-to-month contract customers churn at 42.7% vs 2.8% for two-year contracts
- Fiber optic users churn at 41.9%, nearly double the DSL rate
- Electronic check users churn at 45.3%, 3x higher than autopay users
- New customers (low tenure) have the highest churn risk

## Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Author
Sourati Sinha
School of Business and Management
CHRIST (Deemed to be University), Bangalore
