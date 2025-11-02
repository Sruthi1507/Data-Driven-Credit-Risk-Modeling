**Overview**

This project explores credit risk analysis and explainability using the LendingClub dataset (2007–2018). The goal is to predict loan default risk and interpret which financial factors most influence a borrower's likelihood to default.
It follows an end-to-end data analytics and machine learning workflow — from data cleaning and feature engineering to model training and explainability with SHAP.
**Tech Stack**
Languages & Libraries: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, CatBoost, SHAP
Environment: Jupyter Notebook
**Project**
Data Cleaning & Preprocessing
Removed missing and inconsistent values
Converted percentage and text-based columns (e.g., int_rate, revol_util, emp_length) to numeric
Unified FICO score ranges into a single column
Encoded categorical variables like home_ownership and purpose
Exploratory Data Analysis (EDA)
Visualized class distribution (Paid vs Default)
Analyzed numerical feature distributions
Created correlation and boxplots to compare risk patterns
Feature Engineering & Model Preparation
Selected key financial attributes (loan amount, interest rate, DTI, FICO, etc.)
Imputed missing values (median for numeric, mode for categorical)
Split data into training and testing sets
Modeling & Explainability
Trained classification models (XGBoost, CatBoost)
Used SHAP (SHapley Additive exPlanations) to interpret model predictions
Identified key drivers: interest rate, FICO score, DTI, and revolving balance
**Results**
Achieved strong model accuracy and interpretability
Default probability driven primarily by interest rate, FICO score, and debt-to-income ratio (DTI)
Visual explainability with SHAP plots highlights individual borrower risk contributions
