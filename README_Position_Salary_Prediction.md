
# Position Salary Prediction using Linear and Polynomial Regression

## Overview
This project demonstrates how to predict employee salary based on job level using:
- Linear Regression
- Polynomial Regression

The use case simulates an HR salary estimation scenario where a candidate falls between two levels.

---

## Problem Statement
The HR team uses a salary structure based on position levels.
A candidate has applied for the role of Regional Manager and has 2 years of experience,
placing them at Level 6.5. The goal is to predict the appropriate salary offer.

---

## Dataset
**Position_Salaries.csv**

### Columns:
- Position
- Level
- Salary

Only **Level** is used as the independent variable and **Salary** as the target variable.

---

## Approach
### 1. Linear Regression
- Built a linear regression model
- Visualized salary vs level
- Observed underfitting due to non-linear data

### 2. Polynomial Regression
- Applied polynomial regression (degree = 4)
- Captured non-linear salary trends
- Achieved better accuracy

---

## Model Diagnostics
- R² Score
- RMSE (Root Mean Squared Error)

Polynomial Regression outperformed Linear Regression with higher R² and lower error.

---

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Excel
- GitHub

---

## Results & Insights
- Salary progression is non-linear
- Polynomial Regression is more suitable
- Predicted salary for Level 6.5 is realistic using polynomial model

---

## Business Impact
- Enables fair salary estimation
- Prevents overpaying or underpaying employees
- Supports data-driven HR decisions

---

## Keywords
linear-regression, polynomial-regression, salary-prediction, machine-learning,
python, excel, data-science, hr-analytics
