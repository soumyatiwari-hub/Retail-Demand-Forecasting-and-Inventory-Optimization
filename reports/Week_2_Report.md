# Week 2 Report – Retail Demand Forecasting & Inventory Optimization

## Objective
Develop forecasting models to predict retail product demand using historical sales data.

## Work Completed

### Feature Engineering
- Created lag features (lag_1, lag_7)
- Created rolling mean and rolling standard deviation
- Added calendar-based features (day, month, year)

### Data Preparation
- Prepared forecasting dataset
- Selected relevant features

### Prophet Forecasting
- Trained Prophet model
- Generated future demand predictions

### Model Evaluation
- Calculated MAE, RMSE, and MAPE
- Compared actual vs predicted values

### LightGBM Model
- Trained LightGBM regressor
- Generated predictions
- Analyzed feature importance

### Model Comparison
- Compared Prophet and LightGBM using MAE
- Selected the better-performing model

## Outcome
Successfully completed forecasting pipeline and evaluated multiple forecasting models.