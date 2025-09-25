# Task 3 — Linear Regression

## Overview

This project implements simple & multiple linear regression on a housing dataset using Scikit-learn. The objective is to understand regression modeling, evaluation metrics, and interpretation of coefficients.

---

## Dataset

Path to dataset used:

```
/Users/pratham/Downloads/Housing 2.csv
```

The dataset contains housing-related features and the target variable `price`.

---

## Files

* `linear_regression_task3.py` — main script for preprocessing, training, evaluation, and saving the model.
* `linear_regression_pipeline.joblib` — saved trained pipeline.
* `coefficients.csv` — feature coefficients exported after training.
* `regression_plot.png` — regression visualization (if applicable).

---

## Requirements

```
scikit-learn
pandas
numpy
matplotlib
joblib
```

Install all dependencies:

```bash
pip install -r requirements.txt
```

---

## Run Instructions

Run the script from terminal:

```bash
python linear_regression_task3.py
```

This will:

* Train a Linear Regression model on the dataset.
* Print evaluation metrics (MAE, MSE, RMSE, R²).
* Save the trained model as `linear_regression_pipeline.joblib`.
* Save coefficients in `coefficients.csv`.
* Save regression plot (if possible) in `regression_plot.png`.

---

## Evaluation Metrics

* **MAE**: Mean Absolute Error
* **MSE**: Mean Squared Error
* **RMSE**: Root Mean Squared Error
* **R²**: Coefficient of Determination

---

## Interview Questions & Answers

**1. Assumptions of linear regression?** Linearity, independence, homoscedasticity, normality, low multicollinearity.
**2. Interpretation of coefficients?** Change in target per one-unit change in feature, others held constant.
**3. R² score?** Proportion of variance explained. Closer to 1 = better.
**4. MSE vs MAE?** MSE penalizes large errors more; MAE is robust to outliers.
**5. Detect multicollinearity?** Correlation matrix, VIF. VIF > 10 = multicollinearity.
**6. Simple vs multiple regression?** Simple: one predictor; multiple: more than one.
**7. Linear regression for classification?** Not directly; use logistic regression.
**8. Violating assumptions?** Leads to biased coefficients, poor predictions, unreliable intervals.

---
