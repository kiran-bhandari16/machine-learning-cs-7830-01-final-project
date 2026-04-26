# Comparative Analysis of Machine Learning Models for Diabetes Prediction
This repository contains the final project for **CS 7830 / Machine Learning**, focused on predicting diabetes using health-related indicators from the **BRFSS 2015 Diabetes Health Indicators dataset**.

## Project Overview

The main goal of this project is to build and compare multiple machine learning models for **binary diabetes classification**. The models were trained using demographic, lifestyle, and health-related features such as **BMI, age, high blood pressure, general health, physical health, income, education, and difficulty walking**.

The project includes:
- data preprocessing and feature preparation
- training multiple machine learning models
- hyperparameter tuning using cross-validation
- model evaluation using different performance metrics
- feature importance analysis for the final model

## Models Used

The following models were trained and compared:
- Logistic Regression
- Naive Bayes
- Decision Tree
- Random Forest
- Isolation Forest

Among these models, **Random Forest** was selected as the final model because it achieved the best overall performance on the dataset.

## Final Model

The final tuned Random Forest model used the following hyperparameters:
- `n_estimators = 100`
- `max_depth = 20`
- `min_samples_split = 8`
- `min_samples_leaf = 4`
- `max_features = "sqrt"`

## Evaluation Metrics

The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

## Key Findings

- Logistic Regression and Random Forest achieved the highest overall accuracy.
- Naive Bayes achieved the best recall and F1-score.
- The final Random Forest model achieved about **86.5% test accuracy**.
- Important features included **BMI, general health, high blood pressure, and age**.

## Repository Contents

This repository includes:
- notebook/code for data preprocessing and model training
- hyperparameter tuning results
- evaluation plots and metrics
- feature importance analysis
- report and project materials

## Conclusion

This project shows that machine learning can be used effectively for diabetes prediction using health indicator data. It also highlights the importance of comparing multiple models and using several evaluation metrics instead of relying only on accuracy.
