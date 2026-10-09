# Car Price Prediction Using Linear Regression

## Overview
This project predicts car prices using multivariate linear regression implemented from scratch with NumPy. The objective is to understand the working of linear regression without relying on machine learning libraries such as scikit-learn.

## Methodology
- Load and inspect the car price dataset using Pandas.
- Select numerical features and use `price` as the target variable.
- Shuffle the dataset and split it into training and testing sets.
- Standardize input features using statistics calculated from the training set.
- Implement the cost function and gradient calculations.
- Train the model using gradient descent.
- Evaluate predictions using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Technologies Used
- Python
- NumPy
- Pandas
- Jupyter Notebook

## Files
- `Car_Price_Prediction.ipynb` — Notebook containing the implementation and evaluation.
- `CarPrice_Assignment.csv` — Dataset used for training and testing.

## Evaluation
The model is evaluated on a held-out test set using MAE and RMSE. The results reflect the performance of the selected numerical features and the implemented linear regression model.

## Implementation Notes
The model uses numerical features only. Categorical features are excluded to keep the implementation focused on multivariate linear regression.

## How to Run
1. Install Python and Jupyter Notebook.
2. Install the required packages:
   ```bash
   pip install numpy pandas jupyter