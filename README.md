# Sales-Forecasting-Inventory-Optimization
# Table of Contents
- Business Problem
- Objective
- Introduction
- Installation
- Usage
- Data
- Analysis
- Evaluation
- Libraries
- Tools

# Business Problem
Retail organizations struggle with inaccurate demand forecasting, leading to:
- Stockouts and lost sales
- Overstocking and excess inventory costs
- Inefficient promotion planning
- Poor store-level demand visibility

# Objective
- Forecast weekly sales at store–department level
- Identify key demand drivers (price, CPI, markdowns, unemployment)
- Engineer time-based and lag features for improved accuracy
- Build a machine learning forecasting model using XGBoost
- Support inventory planning and replenishment strategy

# Introduction
This project builds a retail demand forecasting system using historical sales, store attributes, economic indicators, and promotional data. An XGBoost regression model is trained to predict weekly sales, enabling proactive inventory optimization and demand planning.

# Installation
- Install required Python libraries
- Open the Jupyter Notebook
- Load the stores.csv, features.csv, and train.csv datasets
- Run all preprocessing, feature engineering, modeling, and evaluation cells

# Usage
- Clean and merge store, feature, and sales datasets
- Handle missing values using forward/backward filling
- Create time features (year, month, week) and lag features
- Train XGBoost regression model
- Generate weekly sales forecasts and performance metrics

# Data
Dataset size: 421,570 rows
Key features:
- Store, Department
- Weekly sales
- Temperature, fuel price, CPI, unemployment
- MarkDown1–MarkDown5
- Holiday indicator
- Store type and size

# Analysis
- Exploratory analysis of sales trends across stores and departments
- Feature engineering with lagged sales variables
- Correlation analysis between economic factors and demand
- Feature importance extraction from XGBoost model

# Evaluation
Model Performance:
- RMSE: 6,742
- MAE: 4,207
- R² Score: 0.91
The model demonstrates strong predictive performance for retail sales forecasting.

# Libraries
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- xgboost

# Tools
- Jupyter Notebook
- Power BI
- Git & GitHub
- Git LFS
- Microsoft Excel
