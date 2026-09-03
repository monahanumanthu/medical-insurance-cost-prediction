# Medical Insurance Cost Prediction using Machine Learning

## Overview

This project uses Linear Regression to predict medical insurance expenses based on customer information such as age, BMI, smoking status, gender, region and number of children.

## Objective

The objective is to build a regression model that can estimate medical insurance expenses from the available customer features.

## Dataset

The dataset contains 1,338 records and 7 features.

Dataset source:
Kaggle - Medical Insurance Cost Prediction
(View the original dataset)[https://www.kaggle.com/datasets/awaiskaggler/insurance-csv]

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/monahanumanthu/medical-insurance-cost-prediction/blob/main/medical_insurance_cost_prediction.ipynb)

## 📌 Project Overview

Target variable:
`expenses`

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Data Loading
2. Exploratory Data Analysis
3. Data Quality Checking
4. Duplicate Removal
5. Feature Engineering
6. One-Hot Encoding
7. Feature Scaling
8. Train-Test Split
9. Linear Regression
10. Model Evaluation
11. Residual Analysis

## Data Preprocessing

- Checked missing values
- Checked and removed duplicate records
- Encoded categorical variables using One-Hot Encoding
- Used `drop_first=True`
- Standardized numerical features using StandardScaler
- Split the dataset into 80% training and 20% testing data

## Model

Linear Regression

## Model Performance

| Metric | Score |
|---|---:|
| MAE | 4177.27 |
| RMSE | 5956.63 |
| R² Score | 0.8069 |

## Key Findings

- Medical expenses are right-skewed.
- Smoking status shows a strong relationship with medical expenses.
- Age and BMI show positive relationships with expenses.
- Categorical variables require encoding before model training.

## Visualizations

The notebook includes:
- Missing-value analysis
- Feature distributions
- Boxplots
- Correlation heatmap
- Categorical feature analysis
- Smoking vs medical expenses
- Pairplot
- Actual vs predicted plot
- Residual plot
- Regression coefficients

## Key Learning

This project helped me understand the complete workflow of a regression problem, from exploring the data and preprocessing features to training, evaluating and interpreting a machine learning model.

## Future Improvements

- Compare Linear Regression with other regression algorithms
- Perform hyperparameter tuning where applicable
- Explore additional feature engineering
- Compare multiple models using consistent evaluation metrics

## Project Files

- `medical_insurance_cost_prediction.ipynb` — Complete implementation
- `requirements.txt` — Required Python libraries
- `README.md` — Project documentation
