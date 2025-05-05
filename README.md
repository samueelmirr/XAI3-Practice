

# XAI3 Practice – Model-Agnostic Explainability with PDP

This repository contains the complete solution for **XAI3** (Explainable Artificial Intelligence), focused on **model-agnostic methods** using **Partial Dependence Plots (PDP)**. 

## 📚 Task Description

The main objective of this task is to use PDPs to explain the behavior of **Random Forest Regressors** applied to two datasets:

1. **Bike Sharing Dataset** – to predict the number of rented bikes (`cnt`)
2. **House Price Dataset** – to predict house prices (`price`)

The exercises explore both **1D and 2D PDPs**, and analyze the influence of different features on model predictions.


## 🔍 Exercises

### 1. 📈 One-Dimensional PDP – Bike Rentals
- Model trained to predict `cnt`
- PDPs for:
  - `days_since_2011`
  - `temp`
  - `hum`
  - `windspeed`
- 🔎 **Question Answered**: Influence of each variable on predicted bike rentals

### 2. 🌡️ Two-Dimensional PDP – Bike Rentals
- 2D PDP with `humidity` and `temperature` as inputs
- Density visualization using `geom_tile()`
- Random sampling used to reduce dataset size
- 🔎 **Question Answered**: Interaction between humidity and temperature on predictions

### 3. 🏠 PDP – House Price Prediction
- Model trained on `kc_house_data.csv` to predict `price`
- Features:
  - `bedrooms`, `bathrooms`, `sqft_living`, `sqft_lot`, `floors`, `yr_built`
- PDPs generated for 4 key variables
- 🔎 **Question Answered**: Influence of variables on predicted house prices





