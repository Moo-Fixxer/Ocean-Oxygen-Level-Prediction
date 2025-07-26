# 🌊 Ocean-Oxygen-Level-Prediction

This project analyzes how depth, temperature, and salinity affect oxygen concentration in seawater. 

Cleaned missing data, removed outliers using z-scores, and normalized features for better ML performance

Using a cleaned and transformed dataset, we applied both linear and non-linear models, with Random Forest Regression achieving the best performance (R² = 0.82, MAE = 0.52).

Used cross-validation and visualization (scatterplots, time series, correlation matrices) to support conclusions

## 📌 Problem Statement
Analyze environmental factors affecting oceanic oxygen concentration and predict oxygen levels using machine learning.

## 🧠 Approach
- Cleaned missing data and removed outliers
- Normalized features using StandardScaler
- Conducted EDA (correlation matrix, scatter plots, time series)
- Built and evaluated models:
  - Random Forest Regressor (R² = 0.8222, MAE = 0.52)
  - Linear Regression (R² = -0.62)
- Used cross-validation to improve generalization

## ✅ Findings
- Depth has the strongest inverse relationship with oxygen levels
- Random Forest handled non-linear features better than Linear Regression
- Further analysis needed on seasonal/geographic patterns

## 🛠 Tools
Python · pandas · matplotlib · scikit-learn · Jupyter
