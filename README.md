# Polynomial Regression on Car Price Dataset

This project demonstrates the use of **Polynomial Regression** to predict car prices using a dataset named `focus.csv`. The dataset contains various numerical and categorical features related to car specifications.

## 🔍 Project Overview

The following steps are included in this notebook:

- **Data Loading & EDA**
  - Displaying feature correlations with a heatmap
  - Pairplot for visualizing feature relationships
- **Data Preprocessing**
  - Label Encoding for categorical variables
  - Polynomial feature transformation (degree = 3)
- **Model Building**
  - Linear Regression on polynomial features
  - Train-test split (70% - 30%)
- **Model Evaluation**
  - R² Score
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

## 📈 Sample Output

```python
R^2 :       0.91
MAE :       2100.45
RMSE :      3200.67
