# 🚲 Seoul Bike Regression Analysis

This project performs a regression analysis on the **Seoul Bike Sharing Demand dataset**, using weather, date, and time-related features to predict the number of rented bikes. The goal is to uncover how environmental and seasonal factors influence urban bike usage.

---

## 📊 Project Overview

- **Dataset**: Seoul Bike Sharing Demand (from UCI Machine Learning Repository)
- **Objective**: Predict the `rented_bike_count` using features like temperature, hour, season, solar radiation, and more.
- **Model Used**: Linear Regression (with future scope for Ridge, Lasso, and Random Forest)
- **Key Techniques**:
  - Data cleaning and feature engineering (e.g. parsing date, encoding categories)
  - Feature selection via `SelectKBest` and heatmap correlation
  - Model training and evaluation using R² and RMSE
  - Visual analysis: seasonal trends, hourly usage, and monthly fluctuations

---

## 📈 Results

- **R² Score**: 0.526  
- **RMSE**: ~433 bikes per prediction  
- Identified top predictors: temperature, hour of day, season, dew point, and solar radiation.
- Visualized trends across time, seasons, and holidays.

---

## 🔧 Files Included

- `regression_model.ipynb` — Full Jupyter Notebook with step-by-step analysis and visualizations
- `SeoulBikeData.csv` — The dataset used for analysis (may be omitted if data is large)
- `README.md` — Project summary and usage guide

---

## 🚀 How to Use

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/seoul-bike-regression.git
