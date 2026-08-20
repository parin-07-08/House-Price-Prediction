# House Price Prediction

A supervised machine learning regression project for predicting house prices using property characteristics, feature engineering, data cleaning, regression model comparison, cross-validation, and hyperparameter tuning.

## Overview

The objective of this project is to predict the price of residential properties based on features such as location, area, number of bedrooms, bathrooms, balconies, and total floor area.

The project follows an end-to-end regression workflow covering:

- Exploratory data analysis
- Missing-value handling
- Feature engineering
- Outlier detection and removal
- Categorical encoding
- Feature scaling
- Target transformation
- Regression model comparison
- Cross-validation
- Hyperparameter tuning
- Final model selection

## Dataset

The dataset consists of:

- `train.csv` — Training data containing property features and the target variable
- `test.csv` — Test data without the target variable
- `sample_submission.csv` — Sample submission format

### Features

| Feature | Description |
|---|---|
| `id` | Unique property identifier |
| `area_type` | Type/category of the property area |
| `availability` | Property availability status |
| `location` | Location of the property |
| `size` | Number of bedrooms/halls/kitchens |
| `total_sqft` | Total property area in square feet |
| `bath` | Number of bathrooms |
| `balcony` | Number of balconies |
| `price` | Target house price |

## Project Workflow

```text
Data Loading
      ↓
Data Understanding & EDA
      ↓
Missing Value Analysis
      ↓
Feature Cleaning & Engineering
      ↓
Outlier Detection
      ↓
Categorical Encoding
      ↓
Feature Scaling
      ↓
Target Transformation
      ↓
Regression Model Comparison
      ↓
Hyperparameter Tuning
      ↓
Final Model Selection
      ↓
Retraining
      ↓
Test Prediction
