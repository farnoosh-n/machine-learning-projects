# House Price Prediction – Tehran

## Project Overview

This project predicts house prices in Tehran using Linear Regression. The goal was to practice data preprocessing and model evaluation.

## Dataset

Dataset: House Price Tehran (public GitHub source). Used for educational purposes.

## Preprocessing

\- Outliers removed using IQR method  
\- Train/Test split (80/20)  
\- Neighborhood encoded using mean price (train data only)  
\- Deposit and rent removed to avoid data leakage

## Model

Linear Regression trained on: Area, Year, Encoded Neighborhood.

## Evaluation

R² Score ≈ 0.41  
Metrics: MAE, MSE

## Technologies

Python, Pandas, NumPy, Scikit-learn, Matplotlib