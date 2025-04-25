# MLZilla Competition - NMIMS Mumbai (Feb 2025)

## Overview
This repository contains the code and solutions for the **MLZilla Competition** organized by NMIMS Mumbai in February 2025. The competition involved analyzing a telecom churn dataset and applying machine learning techniques to predict customer churn.

### Objective
The goal of this project was to predict whether a customer will churn or not based on various features provided in the dataset. The final model achieved an accuracy of **79%**.

## Project Summary
The main steps involved in the competition included:
- **Data Preprocessing**: Cleaning and transforming the raw dataset.
- **Feature Engineering**: Creating new features that improve the model's predictive power.
- **Balancing the Dataset**: Applying the **SMOTE** technique to handle class imbalance.
- **Model Training**: Using multiple machine learning algorithms (e.g., Random Forest, XGBoost, Logistic Regression).
- **Model Evaluation**: Evaluating the performance of different models using metrics such as accuracy, precision, recall, and F1-score.

## Key Techniques Used
- **SMOTE (Synthetic Minority Over-sampling Technique)**: Used to balance the dataset by generating synthetic samples for the minority class.
- **Feature Engineering**: Applied domain-specific knowledge to create new features and improve model performance.
- **Machine Learning Models**: 
  - Random Forest
  - XGBoost
  - Logistic Regression

## Installation

### Prerequisites
Ensure you have the following Python libraries installed:
- Python 3.x
- `pandas`
- `numpy`
- `scikit-learn`
- `imbalanced-learn`
- `matplotlib`
- `xgboost`

To install the required libraries, run:
```bash
pip install -r requirements.txt
