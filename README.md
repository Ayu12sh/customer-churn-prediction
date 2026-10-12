# Customer Churn Prediction

An end-to-end machine learning classification project that predicts customer churn using the IBM Telco Customer Churn dataset.

## Project Overview

Customer churn is an important business problem because retaining existing customers can be more valuable than continually replacing customers who leave.

This project analyzes customer demographic, account, service, and billing information to identify churn patterns and build machine learning models that predict whether a customer is likely to churn.

## Machine Learning Workflow

- Data loading and exploration
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Train/test split
- Categorical feature encoding
- Numerical feature scaling
- Logistic Regression
- Random Forest
- Model evaluation and comparison
- Feature importance analysis
- Customer churn probability prediction

## Models

Two classification algorithms were trained and compared:

- Logistic Regression
- Random Forest

Logistic Regression produced the strongest overall performance.

## Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 80.53% | 65.15% | 57.49% | 61.08% | 0.8361 |
| Random Forest | 78.75% | 62.89% | 48.93% | 55.04% | 0.8199 |

## Key Results

- Analyzed 7,032 customer records after data cleaning.
- Logistic Regression achieved 80.53% accuracy.
- Logistic Regression achieved a ROC-AUC score of 0.8361.
- Evaluated models using accuracy, precision, recall, F1 score, ROC-AUC, and confusion matrix.
- Used Random Forest feature importance to investigate influential customer characteristics.
- Generated churn predictions and churn probabilities for individual customers.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Business Application

The model could help businesses identify customers with elevated churn risk and prioritize retention strategies, targeted offers, and customer engagement efforts.

## Future Improvements

Potential improvements include:

- Hyperparameter tuning
- Cross-validation
- Additional feature engineering
- Classification threshold optimization
- Testing additional machine learning algorithms

## Project File

The complete analysis, model training, evaluation, and predictions are available in:

`customer_churn_prediction.ipynb`
