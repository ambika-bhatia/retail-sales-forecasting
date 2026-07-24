# Retail Sales Forecasting - Rossmann Store Sales

Predicting daily store sales for 1,115+ Rossmann stores using historical data and machine learning.

## Overview
Built an end-to-end forecasting pipeline — from data cleaning and EDA to feature engineering and modeling — to predict daily retail sales. Along the way, uncovered some interesting patterns in the data (like why average Sunday sales are almost zero ).

## Dataset
[Rossmann Store Sales - Kaggle](https://www.kaggle.com/c/rossmann-store-sales) — ~1M records, 1,115 stores, 2013–2015.

## Approach
- Cleaned and merged store + sales data
- Explored seasonality, promotions, and holiday effects
- Engineered lag and rolling-average features to capture sales momentum
- Used a time-based train-test split (no data leakage)
- Trained a Random Forest Regressor

## Results
- **MAPE: 10.4%**
- **RMSE: ~1003**
- Historical sales trends turned out to be the strongest predictor — more than promotions or store type.

## Tech Stack
Python · pandas · matplotlib · scikit-learn · Jupyter Notebook
