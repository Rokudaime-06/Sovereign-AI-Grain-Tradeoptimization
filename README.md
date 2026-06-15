# Machine Learning Application: Predictive Modeling for Crop Import Optimization

This repository contains a baseline machine learning pipeline developed as a practical application to predict required grain import volumes based on continuous environmental and economic inputs.

## 📊 Pipeline Architecture & Metrics
- **Algorithm:** RandomForestRegressor (100 estimators)
- **Feature Scaling:** MinMaxScaler (0-1 range)
- **Dataset Size:** 500 simulated campaigns
- **Model R² Accuracy Score:** **98.71 %**
- **Mean Absolute Error (MAE):** **14,254 Tonnes**

## 💻 Script Functionality
The pipeline splits the processed features into training and testing sets (80/20), applies feature scaling to prevent dimension bias between variables, and evaluates performance using standard metrics. All computations are executed locally.
