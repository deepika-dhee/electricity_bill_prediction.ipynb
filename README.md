Electricity Bill Prediction using Ridge Regression

Project Overview

This project predicts electricity bills using machine learning.

Linear Regression and Ridge Regression are implemented and compared using MAE, RMSE, and R². Different alpha values are tested, and 5-Fold Cross-Validation is used to select the best alpha for the final Ridge Regression model.

Dataset

The dataset contains information about:

* Appliance usage
* Monthly hours
* Tariff rate
* City
* Company
* Electricity bill

Machine Learning Methods

* Linear Regression
* Ridge Regression
* Alpha Testing
* 5-Fold Cross-Validation

Data Preprocessing

* Numerical feature scaling using StandardScaler
* Categorical feature encoding using OneHotEncoder
* Train-test split

Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

Project Flow

Dataset → Preprocessing → Linear Regression → Ridge Regression → Model Comparison → Alpha Testing → 5-Fold Cross-Validation → Best Alpha → Final Ridge Model → Evaluation → Coefficient Analysis → Actual vs Predicted
Tools and Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook
