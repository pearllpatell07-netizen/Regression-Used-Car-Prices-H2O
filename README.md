# Regression Analysis – Used Car Sales (H2O AutoML)

## Project Overview
This project predicts the selling price of used cars using regression modeling with H2O AutoML.

The goal was to identify the best-performing regression models and compare them using RMSE and other evaluation metrics.

## Dataset
- File: dataset_regression_car_prices.csv
- Target variable: selling_price
- Features include:
  - year
  - present_price
  - kms_driven
  - fuel_type
  - seller_type
  - transmission
  - owner

## Methodology
- Imported dataset into H2O Flow
- Used H2O AutoML with:
  - Problem type: Regression
  - Response variable: selling_price
- AutoML automatically trained multiple models including:
  - Deep Learning
  - Stacked Ensembles

## Results
The leaderboard ranks models based on RMSE (lower is better).
A snapshot of the top-performing models is included below.

## Tools Used
- H2O Flow
- H2O AutoML
- Regression Modeling

## Author
Pearl Patel  
Master’s in Business Analytics
