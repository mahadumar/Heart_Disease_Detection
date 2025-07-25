# Task 3: Heart Disease Prediction

## Objective

Build a machine learning model to predict whether a person is at risk of heart disease based on their medical features.

## Dataset

- **Name**: Heart Disease UCI Dataset
- **Source**: [Kaggle - UCI Heart Disease](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
- **Shape**: 303 rows × 14 columns
- **Target Variable**: `target` (1 = disease present, 0 = no disease)

## Models Applied

- Logistic Regression

## Evaluation Metrics

- Accuracy
- Confusion Matrix
- ROC Curve & AUC Score

## Key Findings

- Achieved an accuracy of ~`0.78%`
- Important features affecting prediction include:
  - `thal`, `cp` (chest pain), `ca` (number of major vessels), `oldpeak`, etc.
- ROC AUC Score: `0.86` 

## Files Included

- `heart_disease_prediction.ipynb`
- `heart.csv`
- `requirements.txt`
