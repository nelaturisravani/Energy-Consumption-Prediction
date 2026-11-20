# Energy Consumption Prediction Model for Efficient Resource Management

An interactive forecasting dashboard that analyzes time-series data and generates future predictions using machine learning and deep learning techniques.



## Overview
This project aims to support efficient resource management by analyzing historical data, identifying patterns, and forecasting future values. It includes a Streamlit dashboard where users can upload a CSV dataset, explore consumption trends, view feature importance, and compare ARIMA and LSTM forecasts.



## Key Features
* **CSV Data Upload:** Analyze custom time-series datasets.
* **Data Preprocessing:** Automatic date/time column detection and missing-value handling.
* **Feature Importance Analysis:** Powered by a Random Forest Regressor.
* **Time-Based Visualizations:** Explore monthly, daily, and hourly trends.
* **ARIMA Forecasting:** Predict future values from historical time-series data.
* **LSTM Forecasting:** Use previous time steps to learn sequential patterns.
* **Recommendations & Alerts:** Displayed directly through the interactive dashboard.



## Technologies Used
* **Programming Language:** Python
* **Dashboard:** Streamlit
* **Data Processing:** Pandas, NumPy
* **Visualization:** Plotly, Matplotlib
* **Machine Learning:** Scikit-learn
* **Time-Series Forecasting:** ARIMA (Statsmodels)
* **Deep Learning:** TensorFlow / Keras (LSTM)
* **Environment:** Jupyter Notebook

---

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/<your-repository>.git
cd <your-repository>
```

### 2. Install Dependencies
```bash
pip install pandas numpy matplotlib plotly streamlit scikit-learn statsmodels tensorflow
```

### 3. Run the Dashboard
```bash
streamlit run energy_dashboard.py
```
Upload a CSV file containing a date/time column and numeric data to explore the visualizations and forecasting results.

---

## Dataset
The repository includes `weather_daily_darksky.csv` as the sample dataset. The dashboard is designed to accept CSV time-series data with a date/time column and at least one numeric column. For energy-consumption analysis, use a dataset that includes energy usage measurements.
