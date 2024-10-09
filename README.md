# credit-risk-classification Report

## Overview of the Analysis

Purpose:
* To create a model to predict if a given loan is high risk for default.

Financial data: 
* The model uses loan size,	interest rate, borrower income,	debt-to-income,	nummber of accounts held, derogatory marks, and total debt as features in the model to ultimately predict the loan status.

Methods: 
* The financial data was split between training data and test data. A logistic regression algorithm was fitted to the training data. Then predictions were made by the model using the test data. These predictions were compared to the actual loan status outcomes in the test data to create a confusion matrix and a classification report.

## Results

Logistic Regression Model:
* Accuracy: 99%
* Precision: 100% for healthy loans, 87% for high-risk loans
* Recall: 100% for healthy loans, 95% for high-risk loans
* Accuracy, precision, and recall all have high scores. This means the model is reliable with little chance for false positives or false negatives, although there is a higher chance of a false positive than a false negative.

## Summary

The logistic regression model performed well. It had high accuracy, precision, and recall. I would recommend this model as a good candidate for the company to implement due to its 99% accuracy. There is a higher chance of a false positive compared to a false negative. This is actually beneficial to the company as this helps to minimize the risk of losses from defaulted loans. While possible, both false positives and false negatives are still unlikely due to the high precision and recall scores.