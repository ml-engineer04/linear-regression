# Gadget Price Prediction using Machine Learning

## Overview
This project uses Machine Learning to predict gadget prices based on their specifications, including brand, device type, RAM, storage, battery capacity, screen size, and other features.

## Project Workflow
- Exploratory Data Analysis (EDA)
- Statistical Analysis and Outlier Detection
- Feature Engineering
- Ordinal Encoding and One-Hot Encoding
- Feature Scaling using StandardScaler and RobustScaler
- Baseline Model Evaluation
- Linear Regression and 5-Fold Cross-Validation
- Residual Analysis
- Log Transformation for improved prediction accuracy
- Model Evaluation and Comparison

## Models
- Dummy Regressor as a baseline
- Linear Regression
- Log-Transformed Linear Regression

## Results

| Metric | Linear Regression | Log-Transformed Model |
|---|---:|---:|
| MAE | $135.79 | $107.87 |
| RMSE | $221.12 | $215.27 |
| MAPE | 33.74% | 16.19% |
| R² | 0.90 | 0.90 |

## Key Findings
- Log transformation reduced the Mean Absolute Error from $135.79 to $107.87.
- MAPE decreased from 33.74% to 16.19%.
- The final model achieved an R² score of approximately 0.90.
- The log-transformed model performed better across the reported error metrics.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Scikit-learn
- Jupyter Notebook

## Skills Demonstrated
Data preprocessing, statistical analysis, feature engineering, categorical encoding, feature scaling, regression modeling, cross-validation, residual analysis, and model evaluation.

## Conclusion
This project demonstrates an end-to-end Machine Learning workflow for gadget price prediction. It explores how data preprocessing and log transformation can improve regression model performance.