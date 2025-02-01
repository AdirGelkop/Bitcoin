# \U0001F4B0 Bitcoin Price Prediction using Machine Learning

## \U0001F4CA Overview
This project leverages **machine learning regression models** to predict Bitcoin's price based on **macroeconomic indicators, stock market data, and commodity trends**. The implementation includes **feature engineering, ensemble learning, and deep learning approaches** to enhance prediction accuracy.

## ✨ Key Features
- \U0001F4C8 **Data Collection**: Fetches historical data from **Yahoo Finance** and **FRED** (Federal Reserve Economic Data).
- \U0001F9E0 **Feature Engineering**:
  - \U0001F4B2 **Copper-to-Gold Ratio**: Indicator of industrial demand.
  - \U0001F4B5 **Money-to-Dollar Ratio**: Represents monetary supply effects.
  - \U0001F30F **Global Velocity**: Measures economic circulation speed.
- \U0001F916 **Modeling Approaches**:
  - \U0001F333 **Random Forest Regressor**
  - \U0001F340 **Gradient Boosting Regressor**
  - \U0001F3A8 **Stacking Regressor (Ensemble Learning)**
- \U0001F4C9 **Evaluation Metrics**:
  - \U0001F522 **R² Score**: Measures variance explanation.
  - \U0001F50E **RMSE**: Measures prediction error.
- \U0001F5BC **Visualizations**:
  - \U0001F4C8 Correlation heatmap (Spearman correlation)
  - \U0001F4D0 Time-series analysis of key features
  - \U0001F4DD Feature importance ranking
  - \U0001F4CA Model comparison (Stacked vs Individual Models)
- \U0001F680 **Bitcoin Price Forecast**: Predicts the next day’s price based on trained models.

## \U0001F527 Implementation
1. \U0001F4C4 **Data Preprocessing**:
   - Collects **macroeconomic indicators, stock prices, and Bitcoin data**.
   - Handles missing values using **forward-fill and backward-fill techniques**.
   - Aligns time-series data for accurate feature extraction.
2. \U0001F9E0 **Feature Engineering**:
   - Computes new macroeconomic indicators to improve model insights.
3. \U0001F916 **Model Training & Evaluation**:
   - Splits dataset into **training (80%) and testing (20%)**.
   - Implements **Random Forest, Gradient Boosting, and Stacking models**.
   - Evaluates models using **R² score** and **RMSE**.
4. \U0001F4B8 **Prediction & Visualization**:
   - Forecasts future Bitcoin prices.
   - Plots **actual vs. predicted prices** for comparison.

## \U0001F4B0 Results Summary
| Model | R² Score |
|--------|-----------|
| \U0001F333 **Random Forest** | 0.9970 |
| \U0001F340 **Gradient Boosting** | 0.9926 |
| \U0001F3A8 **Stacked Model** | 0.9970 |

- \U0001F50D **Stacking Regressor** performed on par with **Random Forest**, indicating **RF dominance in ensemble learning**.
- \U0001F4A1 Feature importance analysis reveals **macroeconomic indicators** significantly impact Bitcoin price movements.

## \U0001F680 Future Enhancements
- \U0001F3AF **Hyperparameter Tuning**: Optimize models for better performance.
- \U0001F916 **Deep Learning Integration**: Implement LSTM/Transformer for time-series forecasting.
- \U0001F4C8 **Multi-day Forecasting**: Extend predictions beyond a single day.

---
\U0001F4DD **Contributors**: Adir Gelkop, Shmuel Lachchakov, Nicole Davidov
\U0001F517 **Email**: Adirgelkop@gmail.com

