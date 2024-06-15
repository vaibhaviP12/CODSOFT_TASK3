# CODSOFT_TASK3

# Customer Churn Prediction

This project aims to predict customer churn for a subscription-based service using historical customer data. Various machine learning algorithms are applied, including Logistic Regression, Random Forests, and Gradient Boosting.

## Introduction

Customer churn is a critical issue for subscription-based businesses. This project leverages machine learning to predict whether a customer will churn based on their demographic and usage behavior data.

## Data Description

The dataset includes the following columns:
- `CustomerId`: Unique identifier for the customer
- `Surname`: Customer's surname
- `CreditScore`: Customer's credit score
- `Geography`: Customer's location
- `Gender`: Customer's gender
- `Age`: Customer's age
- `Tenure`: Number of years the customer has been with the company
- `Balance`: Customer's account balance
- `NumOfProducts`: Number of products the customer has with the company
- `HasCrCard`: Whether the customer has a credit card (1=Yes, 0=No)
- `IsActiveMember`: Whether the customer is an active member (1=Yes, 0=No)
- `EstimatedSalary`: Customer's estimated salary
- `Exited`: Whether the customer has exited (churned) (1=Yes, 0=No)

## Exploratory Data Analysis (EDA)
EDA is performed to understand the data distribution and relationships between features. Visualizations include histograms, count plots, and a correlation heatmap.

## Model Training
Models used:

Logistic Regression
Random Forest
Gradient Boosting
Hyperparameter tuning is done using GridSearchCV.

## Model Evaluation
Evaluation metrics include:

Accuracy
Precision
Recall
F1 Score
ROC AUC

## Model Interpretation
Feature importance is analyzed for Random Forest and Gradient Boosting models to understand which features contribute most to predicting churn.
