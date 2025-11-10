# 🚗 Day 03 - Car Price Prediction with Regression Models
**Project from the "Mastering Applied Data Science Bootcamp"**

This repository contains my study project on predicting **car prices** using regression techniques. The goal was to analyze historical car data, engineer useful features, and build models that can predict prices with high accuracy.

---

## 🔹 Project Overview

The project follows a structured workflow:

1. **Exploratory Data Analysis (EDA)**
   - Load and inspect car datasets
   - Analyze distributions, correlations, and missing values
   - Visualize relationships using plots (heatmaps, scatter plots, boxplots, violin plots)

2. **Feature Engineering**
   - Transform categorical features into numeric format
   - Select relevant features based on correlation with the target variable (`Price`)
   - Normalize data for certain models

3. **Hypothesis Testing**
   - Test relationships between key variables using p-values
   - Example: mileage vs. price

4. **Regression Modeling**
   - Train multiple regression models:
     - Linear Regression
     - Ridge, Lasso, ElasticNet
     - Decision Tree, Extra Trees, XGBoost
   - Evaluate models using:
     - R² Score
     - Root Mean Squared Error (RMSE)
     - Mean Absolute Error (MAE)

5. **Model Comparison**
   - Compare model performance and select the best one
   - Visualize residuals to check for distribution and outliers

---

## 🔹 Key Results

- The **Extra Trees Regressor** achieved the best performance
- Accuracy: **~99%**
- Root Mean Squared Error (RMSE): **$944**
- The model successfully predicts car prices with high reliability

