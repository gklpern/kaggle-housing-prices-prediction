# House Price Prediction Project

This project uses various machine learning models to predict house prices based on a dataset containing features such as lot size, location, and year built. 

## Project Overview

- **Objective:** Predict the sale prices of houses using a variety of machine learning models.
- **Tech Stack:** Python, Pandas, Scikit-learn, Seaborn, Matplotlib, TensorFlow
- **Models used:**
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - Neural Network

## Steps Involved

1. **Data Loading & Cleaning:**
   - The dataset is loaded from CSV files and cleaned by handling missing values, outliers, and categorical encoding.

2. **Feature Engineering:**
   - New features such as `HouseAge`, `TotalSF`, `TotalBathrooms`, and `TotalPorchArea` are created to improve model performance.

3. **Data Preprocessing:**
   - Scaling of numerical features and one-hot encoding of categorical variables are applied.
   - Missing values are imputed with appropriate strategies.

4. **Model Training & Evaluation:**
   - Various models such as Linear Regression, Random Forest Regressor, Gradient Boosting Regressor, and a Neural Network are trained and evaluated.
   - Performance metrics such as R², Mean Squared Error (MSE), and Mean Absolute Error (MAE) are used for evaluation.

5. **Final Model Prediction:**
   - The best model is selected based on performance metrics and used for predicting the sale prices of houses.

Usage:


1. Load the dataset:
   ```python
   import pandas as pd
   train_df = pd.read_csv('train.csv')
   test_df = pd.read_csv('test.csv')

