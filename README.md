# California Real Estate Price Prediction (Capstone Assignment 20.1)

## Project Overview
This project aims to develop a machine learning model that predicts **real estate prices in California** using publicly available housing datasets. The goal is to help buyers, sellers, investors, and policymakers better understand the key drivers of housing prices and improve market transparency through data-driven insights.

## Research Question
**How accurately can we predict California real estate prices using property-level features such as location, size, and housing characteristics?**

## Dataset
- **Source:** Public real estate dataset (Kaggle / open data)
- **File:** `housing.csv`
- **Target variable:** `price`
- **Features include:**
  - bedrooms, bathrooms  
  - square footage (`sqft_living`, `sqft_lot`, `sqft_basement`)  
  - property attributes (`view`, `waterfront`, `condition`, `grade`)  
  - location variables (`lat`, `long`, `zipcode`)  
  - year built / renovated (`yr_built`, `yr_renovated`)


## Findings (Summary of Key Insights)

### 1) Strong Predictors of House Price

### 2) Location Strongly Impacts House Prices

### 3) Outliers Exist and Affect Model Stability

### 4) Feature Engineering Adds Useful Signals

## Modeling (Baseline)
Baseline regression models:
- Linear Regression
- Ridge Regression

Preprocessing steps:
- numeric scaling
- imputation
- one-hot encoding categorical variables

Evaluation metrics:
- RMSE
- MAE
- R² score
