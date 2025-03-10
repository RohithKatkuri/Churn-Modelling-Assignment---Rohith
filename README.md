# Churn-Modelling-Assignment---Rohith

# Telco Customer Churn Analysis

## Overview

This Jupyter Notebook is an assignment focusing on customer churn analysis using the Telco Customer Churn dataset. The notebook covers:

- Data cleaning
- Exploratory Data Analysis (EDA)
- Model training and evaluation
- Feature importance analysis
- Model tuning with hyperparameter optimization

## Dataset

The dataset contains:

- 7000+ rows and 21 columns
- Customer demographics, services, billing details
- Churn status as the target variable

## Prerequisites

Ensure you have the following dependencies installed before running the notebook:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Data Cleaning

- Loaded dataset using Pandas
- Handled missing values by imputing or dropping
- Encoded categorical variables using one-hot encoding (e.g., `Contract`, `PaymentMethod`)

## Exploratory Data Analysis (EDA)

- Calculated churn rates
- Visualized feature distributions (e.g., `tenure` vs. `churn` with Seaborn)
- Conducted correlation analysis to identify key predictors

## Machine Learning Models Implemented

- Logistic Regression
- Random Forest Classifier
- Hyperparameter tuning using GridSearchCV and RandomizedSearchCV

## Model Evaluation

- Measured accuracy, precision, and recall
- Analyzed confusion matrices and classification reports

## Insights

- Identified key factors driving customer churn:
  - Customers with **monthly contracts** have a significantly higher churn rate compared to those with long-term contracts.
  - **Senior citizens** tend to have a slightly higher churn rate than younger customers.
  - **Electronic check payments** are correlated with higher churn, while customers using automatic payments tend to stay longer.
- **Feature Importance:**
  - **Tenure (length of customer relationship)** is one of the strongest predictors of churn—longer tenure reduces churn probability.
  - **Contract type (monthly, yearly, two-year)** heavily influences customer retention.
  - **Tech support and online security services** show a strong correlation with lower churn—customers with these services are more likely to stay.
- **Model Performance:**
  - **Random Forest performed better** than Logistic Regression in predicting churn, with higher accuracy and recall.
  - **Hyperparameter tuning** slightly improved the model's precision and recall scores.
  - The **confusion matrix** showed that false positives (predicting a customer will churn when they won’t) were relatively common.


## Contact
katkurirohith1622@gmail.com

