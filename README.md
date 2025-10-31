# Human Productivity Prediction using Machine Learning Models.
## Project Overview :
While doing my machine learning course CSE427 at BRAC univarsity I did this project. I tried to predict human productivity scores based on lifestyle habits, digital behavior, and work patterns. Instead of guessing how work hours, sleep, social media, stress, or satisfaction affect productivity, my model learns real patterns from a 30K row dataset(collected from kaggle). The goal is to help people and organizations understand what truly drives productivity and detect unfair model behavior across different groups.
## What I did :
- Useed multiple models like Random Forest, LightGBM, XGBoost, MLP, Linear Regression
- Added Feature Engineering
- Applied fairness checks across gender, age, and job types
- Used SHAP explainability to show why the model makes decisions

## Results :
Linear Regression 0.905752 (R²), 0.582695 (RMSE), 0.428623 (MAE) 
Random Forest     0.924462 (R²), 0.521661 (RMSE), 0.401924 (MAE)
XGBoost           0.914157 (R²), 0.556105 (RMSE), 0.429498 (MAE)
LightGBM          0.924686 (R²) 0.520886 (RMSE), 0.401280 (MAE)

LightGBM performed best. 
![R²](https://img.shields.io/badge/Accuracy-R%C2%B2%20%3D%200.92-brightgreen)
