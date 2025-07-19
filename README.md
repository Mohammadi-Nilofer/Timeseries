# ⏳ Time Series Analysis - PJME Energy Consumption

## 📌 Project Overview

This project focuses on analyzing hourly energy consumption data from PJME (PJM East), a regional electricity provider in the U.S. The primary goal is to explore and understand the temporal patterns, seasonality, and trends within the dataset to support energy demand forecasting.

---

## 📊 Dataset

- **Source:** PJME_hourly.csv  
- **Features:**
  - `Datetime`: Timestamps at hourly frequency
  - `PJME_MW`: Electricity consumption in megawatts

---

##  Objectives

- Preprocess and clean the time series data
- Visualize trends, seasonality, and autocorrelation
- Resample and smooth the data for better pattern detection
- Lay the groundwork for future forecasting models (ARIMA, Prophet, etc.)

---

## ⚙️ Key Steps

1. **Data Cleaning**
   - Converted `Datetime` to `datetime64` type
   - Set `Datetime` as the index for time series operations

2. **Exploratory Data Analysis**
   - Line plots to understand usage patterns
   - Heatmaps and seasonal plots
   - Rolling means and resampling (daily, monthly)

3. **Stationarity Checks**
   - Applied Augmented Dickey-Fuller (ADF) test
   - Visual inspection of rolling mean & std

4. **Feature Engineering**
   - Extracted time-based features (hour, day, month, etc.)
   - Aggregated and resampled data at various granularities

---

## 📌 Technologies Used

- **Language:** Python
- **Libraries:**
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – Visualization
  - `statsmodels` – Statistical tests and models
  - `warnings`, `datetime` – Utility

---

## 📈 Visual Insights

A range of plots were generated to understand:
- Hourly and daily usage patterns
- Seasonality across different months and years
- Distribution of energy consumption
- Trends using rolling averages

---

## 🚀 Future Scope

This notebook prepares the data and analysis pipeline for advanced time series forecasting models such as:
- **ARIMA / SARIMA**
- **Facebook Prophet**
- **LSTM / Deep Learning-based Time Series Models**

---

## 🙌 Acknowledgements

Grateful to the mentors and contributors who guided the development of this project.

---


