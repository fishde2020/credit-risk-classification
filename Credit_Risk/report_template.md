# Module 12 Report Template

## Overview of the Analysis
In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this report is to use various techniques to train and evaluate a transgression model to determine the accuracy for healthy and high risk loans.

The lending data consisted of the following: loan size, interest rate, borrower income, debt to income ratio, number of accounts, derrogatory marks, total debt and loan status.

The "target" variable, y, is the loan_status which can be classified as 0 or 1. 0 represents a high risk loan, and 1 represents a high risk loan.

All other data is within the "features" variable, x.

Stages of the Machine Learning Process:

Data Collection and Preparation
Model Selection
Model Training
Model Prediction
Model Utilization
The Logistic Regression Model with the resampling method was used to determine credit risk classification accuracy.

The model's performance was evaluated based on the accuracy score.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

Machine Learning Model 1 - Logistic Regression:

Accuracy: 94.92%
Precision: 1.00/ 0.87
Recall Scores: 1.00/ 0.90


Machine Learning Model 2 - Logistic Regression w/ Resampled Data:

Accuracy: 99.34%
Precision: 1.00/ 0.86
Recall Scores: 0.99/ 0.99

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

Based on the findings of Machine Learning Model 1 compared to Machine Learning Model 2, I recommend using Model 2, Logistic Regression with Resampled Data.
Since the Logistic Regression with Resampled Data model has higher accuracy and recall scores, this model performs the best.
The higher recall score means this model is better at identifying positive and negative examples.
Performance is impacted by the type of problems we are trying to solve. 