# Week 4 — Logistics Delivery-Time Prediction

End-to-end regression project for predicting food delivery time in minutes.

## Dataset
Public `Food_Delivery_Times.csv` dataset:
The dataset has 1,000 records and includes distance, weather, traffic, time of day, vehicle type, preparation time, courier experience, and `Delivery_Time_min` as the target.

## Pipeline
1. EDA and target distribution
2. Missing-value handling and type validation
3. Outlier inspection
4. Feature engineering
5. Train/test split
6. Linear Regression, Random Forest, HistGradientBoosting comparison
7. Randomized hyperparameter tuning
8. Held-out MAE/RMSE/R² evaluation
9. Feature importance
10. Predicted-vs-actual visualization

## Engineered features
- `Distance_sq`
- `Prep_Distance_Interaction`
- `Distance_per_Experience`
- `Traffic_Score`
- `Peak_Period`
