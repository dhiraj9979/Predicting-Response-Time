# Predicting-Response-Time
NYC 311 Complaint Response Time Prediction
A Machine Learning Pipeline for Forecasting Service Response Delays

Project Overview

This project builds an end-to-end machine learning system to predict the response time (in hours) for NYC 311 service complaints.
By forecasting delays before they occur, NYC agencies can allocate resources, detect bottlenecks, and improve service delivery for millions of residents.

The solution includes:

Automated data cleaning & preprocessing

Feature engineering for date/time, weather, location, and complaint metadata

Feature selection using Mutual Information

Model training with multiple algorithms (Linear, Ridge, Lasso, XGBoost, LightGBM, CatBoost, MLP)

GPU-accelerated training where possible

Hyperparameter tuning

SHAP-based explainability

Saving best model + preprocessor for deployment

How to Run the Project:
1. Install Dependencies - pip install -r requirements.txt
2. (Optional) Enable GPU support
3. Run the training pipeline
4. Run SHAP explainability
