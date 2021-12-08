# Santander Customer Transaction Prediction

## Description

This project aims to build a binary classification prediction model to predict a santander customer transaction. 

The dataset contains 201 anonymized featues with 200,000 records. THe target column is an imbalanced binary response.

## Exploratory Analysis and Preprocessing

- Performing EDA, an imbalanced dataset was noticed. Only 10% of the dataset has label '1' while the remaning 90% with label '0'.
- The datset was split into train and test and was standardized

## Model Selection

- Logistic Regression, Decision Tree, Naive Bayes and XGBoost models were used.
- The test set was classified using evaluation metrics and hyperparameter tuning to determine best classifier. 

## Analysis of Results

|Algorithm|Result|
|---------|------|
|Logistic Regression| 75.5%|
|Decision Tree|67.6%|
|Naive Bayes|92.1%|
|XGBoost|98.5%|

## Python version

Python version 3.9.7

## Package version

- numpy version: 1.21.1 
- matplotlib version: 3.4.2 
- sklearn version: 0.24.2 
- pandas version: 1.3.1 
- xgboost version: 1.3.3 
- shap version: 0.39.0
