# Credit Risk Classification

## Overview of the Analysis

This analysis evaluates loan risk based on historical lending data.

* Purpose is to determine creditworthiness of borrowers.
* Used a dataset of historical lending from a peer-to-peer lending company.
* The dataset included 77,536 loan entries.
* The features include
    * Loan Size
    * Interest Rate
    * Borrower Income
    * Debt to Income
    * Number of Accounts
    * Derogatory Marks
    * Total Debt
* The label used is Loan Status.
* The variables were separated and data was split into training and testing datasets to train the model.
* Used a Logistic Regression model for making predictions.

## Results

* Logistic Regression Model:
    * Model Accuracy = 99.18%
    * Healthy Loan Precision = 100%
    * Healthy Loan Recall = 99%
    * High-Risk Loan Prescision =  85%
    * High-Risk Loan Recall = 91%

## Summary

The near perfect healthy loan precision means there are very few false positives, or qualified loans that turn bad. This healthy loan precision along with high model accuracy make the model ideal for predicting if a potential borrower is qualified to borrow.
