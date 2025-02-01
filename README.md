# 💰 Bitcoin Price Prediction using Machine Learning

## 📊 Overview

This project leverages **machine learning regression models** to predict Bitcoin's price based on **macroeconomic indicators, stock market data, and commodity trends**. The implementation includes **feature engineering, ensemble learning, and deep learning approaches** to enhance prediction accuracy.

## ✨ Key Features

- 📈 **Data Collection**: Fetches historical data from **Yahoo Finance** and **FRED** (Federal Reserve Economic Data).
- 🧠 **Feature Engineering**:
  - 💲 **Copper-to-Gold Ratio**: Indicator of industrial demand.
  - 💵 **Money-to-Dollar Ratio**: Represents monetary supply effects.
  - 🌍 **Global Velocity**: Measures economic circulation speed.
- 🤖 **Modeling Approaches**:
  - 🌲 **Random Forest Regressor**
  - 🍀 **Gradient Boosting Regressor**
  - 🎨 **Stacking Regressor (Ensemble Learning)**
- 📉 **Evaluation Metrics**:
  - 🔢 **R² Score**: Measures variance explanation.
  - 🔍 **RMSE**: Measures prediction error.
- 🖼 **Visualizations**:
  - 📈 Correlation heatmap (Spearman correlation)
  - 📊 Time-series analysis of key features
  - 📜 Feature importance ranking
  - 📉 Model comparison (Stacked vs Individual Models)
- 🚀 **Bitcoin Price Forecast**: Predicts the next day’s price based on trained models.

## 🔧 Implementation

1. 📄 **Data Preprocessing**:
   - Collects **macroeconomic indicators, stock prices, and Bitcoin data**.
   - Handles missing values using **forward-fill and backward-fill techniques**.
   - Aligns time-series data for accurate feature extraction.
2. 🧠 **Feature Engineering**:
   - Computes new macroeconomic indicators to improve model insights.
3. 🤖 **Model Training & Evaluation**:
   - Splits dataset into **training (80%) and testing (20%)**.
   - Implements **Random Forest, Gradient Boosting, and Stacking models**.
   - Evaluates models using **R² score** and **RMSE**.
4. 💹 **Prediction & Visualization**:
   - Forecasts future Bitcoin prices.
   - Plots **actual vs. predicted prices** for comparison.

## 💰 Results Summary

| Model                          | R² Score |
| ------------------------------ | -------- |
| 🌲 **Random Forest**           | 0.9970   |
| 🍀 **Gradient Boosting**       | 0.9926   |
| 🎨 **Stacked Model**           | 0.9970   |

- 🔎 **Stacking Regressor** performed on par with **Random Forest**, indicating **RF dominance in ensemble learning**.
- 💡 Feature importance analysis reveals **macroeconomic indicators** significantly impact Bitcoin price movements.

---

📝 **Contributors**: Adir Gelkop, Shmuel Lachchakov, Nicole Davidov
🔗 **Email**: Adirgelkop@gmail.com

