# 📈 Real-Time Series Modeling for BTC/USD Price Prediction

This project focuses on forecasting Bitcoin (BTC) prices using time series models such as ARIMA and Facebook Prophet. It aims to help analysts and investors understand and anticipate price movements based on historical daily data.

---

## 🔍 Project Overview

- **Goal**: Predict the future closing price of Bitcoin using historical data.
- **Techniques Used**:
  - Stationarity checks using ADF Test
  - Seasonal decomposition
  - ARIMA model (auto-configured via pmdarima)
  - Facebook Prophet model
- **Evaluation Metrics**: MAE, RMSE

---

## 🧠 Models Implemented

1. **ARIMA (Auto Regressive Integrated Moving Average)**  
   Automatically selected parameters using `pmdarima.auto_arima` and fit on training data.

2. **Facebook Prophet**  
   Used for trend and seasonality detection with future forecasting capabilities.

---

## 🗂️ Dataset

- **File**: `Data_RTSM.csv`
- **Source**: Historical BTC/USD prices
- **Columns**:
  - `date`: Daily timestamp
  - `open`, `high`, `low`, `close`: Price indicators
  - `Volume BTC`, `Volume USD`: Trading volume data

---

## 🛠️ Requirements

Install the required libraries using:

```bash
pip install -r requirements.txt
```
or manually
```
pip install pandas numpy matplotlib statsmodels pmdarima prophet scikit-learn
```
---

## 🚀 How to Run

1. Clone this repository.
2. Run the Jupyter notebook Code_RTSM.ipynb.
3. The notebook will:
   - Load and visualize the dataset
   - Test for stationarity
   - Apply ARIMA and Prophet for forecasting
   - Visualize and compare model performance

---

## 📊 Outputs
- Forecast plots for both ARIMA and Prophet
- Evaluation metrics (MAE, RMSE) for model comparison

---

## 📌 Note
- Dataset is daily BTC/USD price data, beginning from 2022.
- Time-based train-test split was used for modeling to preserve temporal dependencies.

---

## ✍️ Author

**Sayan Das**  
*B.Tech + M.Tech in Mechanical & Financial Engineering*  
*Indian Institute of Technology, Kharagpur (IIT Kharagpur)*

---
