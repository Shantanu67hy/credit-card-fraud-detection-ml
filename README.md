# Credit Card Fraud Detection using Machine Learning

## Overview

This project detects fraudulent credit card transactions using machine learning.
The dataset is highly imbalanced, so SMOTE was used to balance the data.

## Features

* Imbalanced data handling using SMOTE
* Multiple model training (Logistic, Random Forest, XGBoost)
* Accuracy comparison graph
* Confusion matrix evaluation
* Best model selection
* Model saving using joblib

## Models Used

* Logistic Regression
* Random Forest
* XGBoost

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Workflow

1. Load dataset
2. Handle imbalance using SMOTE
3. Train multiple models
4. Compare accuracy
5. Select best model
6. Save trained model

## Tech Stack

Python, Scikit-learn, XGBoost, Pandas, Matplotlib

## Output

Best model saved as `fraud_model.pkl`
