# Linear Regression

## What it does
Linear regression predicts a numerical value by fitting a line to observed data.

## Equation
\[
\hat{y}=mx+c
\]

- `x`: input feature
- `ŷ`: predicted output
- `m`: slope
- `c`: intercept

## Training formulas

\[
m=\frac{\sum(x-\bar{x})(y-\bar{y})}{\sum(x-\bar{x})^2}
\]

\[
c=\bar{y}-m\bar{x}
\]

## Evaluation metrics

- **Residual:** Actual value − Predicted value
- **MAE:** Mean of absolute residuals
- **MSE:** Mean of squared residuals

## Python
- `model.fit(X, y)`: learns the relationship.
- `model.predict(X)`: generates predictions.
- `model.coef_`: learned coefficient(s).
- `model.intercept_`: learned intercept.

## Key distinction
Linear regression predicts numerical values. Classification algorithms predict categories.

## Repository experiments
- `manual.ipynb`: calculate the model and metrics using NumPy.
- `sklearn_regression.ipynb`: fit and evaluate the model using scikit-learn.