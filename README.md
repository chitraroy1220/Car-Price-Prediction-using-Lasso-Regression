# Car-Price-Prediction-using-Lasso-Regression
This repository contains a machine learning project that demonstrates how Lasso Regression (L1 Regularization) can be used for car price prediction. 
The project focuses on feature selection, handling multicollinearity, and evaluating model performance using appropriate metrics.

**Project Overview**

  Predicting car prices is a common regression problem in machine learning. In this project:
  We use Lasso Regression to predict car prices
  Perform data preprocessing and feature scaling
  Analyze feature importance (coefficients shrinkage)
  Evaluate the model using R² score, RMSE, and ROC-AUC (if classification thresholding is applied)

📊 Dataset Description

The dataset contains information about cars and their corresponding prices.

**Features**

| Feature Name     | Description                          |
|------------------|--------------------------------------|
| Car_Name         | Name of the car                      |
| Year             | Manufacturing year                  |
| Selling_Price    | Price of the car (Target variable)  |
| Present_Price    | Showroom price                      |
| Driven_kms       | Distance driven                     |
| Fuel_Type        | Petrol / Diesel / CNG               |
| Selling_type     | Dealer / Individual                 |
| Transmission     | Manual / Automatic                  |
| Owner            | Number of previous owners           |


Note: Categorical variables are encoded before training.

**Model Used**
🔹 Lasso Regression
    Linear regression with L1 regularization
    Helps in feature selection by shrinking less important feature coefficients to zero
    Reduces overfitting and improves interpretability

**Libraries**
  Python, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

**Model Evaluation**
The model is evaluated using:
  R² Score – Model accuracy
  Mean Squared Error (MSE)
  Root Mean Squared Error (RMSE)
  ROC-AUC Curve (only if binary classification is derived)

Note: ROC-AUC is computed only when both classes are present in test data.
