# Machine Learning Projects

## Overview
This repository contains a collection of **end-to-end Machine Learning projects** focused on solving real-world problems through data preprocessing, feature engineering, predictive modeling, model evaluation, and optimization.

# Projects-

# 🚲 Bike Sharing Demand Prediction

## 📌 Project Overview

This project focuses on predicting **hourly bike rental demand in Seoul, South Korea**, using historical rental data along with weather, seasonal, holiday, and time-based factors. The objective is to build a reliable machine learning model that can help bike-sharing operators **anticipate demand, optimize fleet availability, and improve operational planning**.

The project uses a dataset containing **8,760 observations and 14 variables**. Through exploratory data analysis, data preprocessing, feature engineering, statistical analysis, and machine learning, the project identifies the key factors influencing bike rental demand.

Multiple regression algorithms were implemented and compared, including **Linear Regression, Lasso, Ridge, Decision Tree, Random Forest, Gradient Boosting, and XGBoost**. Hyperparameter tuning and cross-validation were performed to improve model performance and reduce overfitting.

### 🎯 Key Objectives

* Analyze historical bike rental and weather patterns.
* Identify key factors influencing bike rental demand.
* Perform data cleaning, preprocessing, and feature engineering.
* Handle outliers, skewness, categorical variables, and multicollinearity.
* Compare multiple regression algorithms.
* Apply **cross-validation and hyperparameter tuning**.
* Evaluate models using **R², RMSE, MAE, and MSE**.
* Develop a model capable of accurately predicting hourly bike demand.

### 💡 Key Insights

The analysis revealed that bike demand varies significantly based on **hour, season, month, working days, temperature, and weather conditions**. Demand was particularly high during **morning and evening hours**, while winter months showed comparatively lower demand.

After evaluating multiple models, the **tuned XGBoost Regressor** delivered the best performance, achieving approximately **93% R² on training data and 90% R² on test data**.

### 🛠️ Tools & Technologies

**Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | XGBoost | Statistical Analysis | Machine Learning | Regression**

### 📈 Business Impact

The model and insights can support **demand forecasting, fleet allocation, bike availability planning, and operational decision-making**, helping bike-sharing services respond more effectively to changing customer demand.
