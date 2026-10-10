# Diabetes Dataset Regression Analysis

## Overview
This project explores various machine learning regression models to predict disease progression based on the Scikit-Learn Diabetes dataset. It compares standard linear models with complex polynomial models and applies regularization techniques to evaluate model performance and feature importance.

## Models & Techniques
- **Linear Regression:** Baseline model for predicting target values.
- **Polynomial Regression (Degree 2):** Explored to capture potential non-linear relationships.
- **Regularization (Ridge & Lasso):** Applied L1 and L2 penalties to analyze feature importance, reduce model complexity, and prevent overfitting.

## Key Findings
- The standard Linear Regression model provided the most balanced performance (Highest R² and lowest MSE).
- Polynomial regression overcomplicated the specific relationships in this dataset, leading to poor generalization.
- Lasso regularization (alpha=1.0) applied a harsh penalty on this specific dataset, zeroing out critical coefficients and degrading overall performance. 

## Technologies Used
- Python
- Scikit-Learn
- Pandas & NumPy
- Matplotlib & Seaborn (for data visualization)
