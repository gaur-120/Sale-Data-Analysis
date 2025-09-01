# Walmart Store Sales Forecasting
This project analyzes historical sales data from Walmart stores to identify trends, perform exploratory data analysis (EDA), and build predictive models for future sales. It is based on the Kaggle Walmart Store Sales Forecasting competition.
# 📌 Project Overview
The goal of this project is to forecast weekly sales for different Walmart stores and departments. The dataset includes:
Store and department information
Historical weekly sales
Economic indicators (CPI, Unemployment, Fuel Price)
Special events and holidays
# 🔍 Key Steps
1. Data Understanding & Cleaning
Merged multiple CSV files: train.csv, features.csv, stores.csv
Converted dates to datetime and extracted features (Year, Month, Week)
Handled missing values and outliers
2. Exploratory Data Analysis (EDA)
Sales distribution, holiday impact, store and department performance
Trend analysis over time
Correlation heatmap to understand feature relationships
3. Feature Engineering
Created time-based features: Year, Month, Week
Built lag features: Lag_1, Lag_52
Added rolling averages for smoothing trends
4. Modeling
Baseline model using Lag-52 approach
XGBoost Regression model for forecasting
Evaluated using Mean Absolute Error (MAE) and Kaggle’s Weighted MAE
5. Visualization
Line plots for sales trends
Bar charts for store/department sales
Feature importance plots from XGBoost
# 🛠️ Tech Stack
Languages: Python
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost

Tools: Google Colab, Kaggle API
