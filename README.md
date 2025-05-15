# Household Energy Consumption Prediction

## Overview
This project focuses on predicting hourly household energy consumption using machine learning techniques. The model is designed to estimate energy usage based on features such as:
- Temperature
- HVAC usage
- Humidity

The dataset used for this project is sourced from Kaggle and contains detailed energy consumption metrics.

---

## Features
- **Exploratory Data Analysis (EDA)**:
  - Performed outlier detection to identify anomalies.
  - Handled missing values through imputation.
  - Applied feature engineering to derive meaningful insights.
  
- **Data Preprocessing**:
  - Normalized data using **MinMaxScaler** to ensure consistent scaling of features.

- **Model Optimization**:
  - Tuned hyperparameters using **Grid Search CV** to find the best-performing parameters.
  - Implemented **K-fold Cross-Validation** to ensure robust model evaluation.

- **Performance Metrics**:
  - Evaluated model using:
    - **Mean Squared Error (MSE)**
    - **R² Score**

---

## Dataset
The dataset includes the following features: **Temperature**, **Humidity**, **SquareFootage**, **Occupancy**, **HVACUsage**, **LightingUsage**, **RenewableEnergy**, **DayOfWeek**, **Holiday**, and **EnergyConsumption** (target variable).

---

## Methodology
1. **Data Preparation**:
   - Handled missing data and performed outlier detection.
   - Normalized numerical features using **MinMaxScaler**.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed feature correlations and distribution.
   - Visualized trends in energy consumption using matplotlib/seaborn.

3. **Model Training**:
   - Experimented with multiple regression algorithms (e.g., Linear Regression, Random Forest Regressor).
   - Used **Grid Search CV** for hyperparameter tuning.

4. **Evaluation**:
   - Validated the model using **K-fold Cross-Validation**.
   - Assessed performance with **MSE** and **R² Score**.


