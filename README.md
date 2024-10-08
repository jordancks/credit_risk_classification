# Module 20 - Credit Risk Classification Report

## Overview of the Analysis
The purpose of this analysis is to build a logistic regression model that predicts credit risk, specifically identifying loans that are high risk versus healthy loans. Using data from the lending_data.csv, machine learning techniques ia used to create a logistic regression model that could help a financial institution assess the likelihood of a loan defaulting based on various features such as loan size, interest rate, borrower income, debt-to-income ratio, and more.

## Results
* Accuracy Score: 99%
* Precision Score:
    Healthy Loan (0): 1.00
    High-Risk Loan (1): 0.86
* Recall Score:
    Healthy Loan (0): 1.00
    High-Risk Loan (1): 0.91

## Summary
The logistic regression model performed exceptionally well, achieving an accuracy score of 99%. It demonstrates nearly perfect precision and recall for predicting healthy loans (class 0). For high-risk loans (class 1), it still shows a strong performance, with an 86% precision score and 91% recall. This means the model is quite effective at identifying loans that are likely to default, though there is a small chance of misclassifying a few high-risk loans as healthy (false negatives).

Given the high recall for high-risk loans, the model is suitable for use by the company in credit risk assessment. It successfully identifies the majority of risky loans, which can be critical for risk mitigation in lending decisions. The model's overall performance is solid even though there may be occasional false positives or false negatioves, it could greatly improvede company's ability to manage credit risk.

I recommend using this model, as it provides a robust and accurate method for predicting loan default risk.