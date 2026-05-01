# ⚡ Electricity Demand Forecasting using ARIMA & LSTM

## 📌 Overview
This project focuses on forecasting household electricity consumption using time series analysis techniques. It compares a classical statistical model (ARIMA) with a deep learning model (LSTM) to evaluate their performance on real-world data.

---

## 🎯 Objectives
- Perform time series analysis on electricity consumption data
- Apply ARIMA for baseline forecasting
- Implement LSTM for deep learning-based forecasting
- Compare model performance using evaluation metrics

---

## 📊 Dataset
- Source: UCI Machine Learning Repository  
- Dataset: Individual Household Electric Power Consumption  
- Features include:
  - Global active power
  - Voltage
  - Global intensity
  - Sub-metering values

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- TensorFlow / Keras

---

## 🔍 Project Workflow

### 1. Data Preprocessing
- Combined Date & Time into datetime format
- Handled missing values
- Converted data types
- Resampled data to daily frequency

### 2. Exploratory Data Analysis (EDA)
- Time series visualization
- Rolling statistics
- Seasonal decomposition
- Stationarity testing (ADF Test)

### 3. ARIMA Model
- Train-test split (80-20)
- Model training with (p,d,q) parameters
- Forecasting future values
- Evaluation using MAE and RMSE

### 4. LSTM Model
- Data normalization using MinMaxScaler
- Sequence generation for time series
- Model building using stacked LSTM layers
- Training and prediction
- Evaluation using MAE and RMSE

### 5. Model Comparison
- Performance comparison between ARIMA and LSTM
- Visualization of prediction results

---

## 📈 Results

| Model  | MAE | RMSE |
|--------|-----|------|
| ARIMA  | XX  | XX   |
| LSTM   | XX  | XX   |

> Replace XX with your actual values

---

## 🧠 Key Insights
- ARIMA performs well for linear trends
- LSTM captures complex and nonlinear patterns better
- LSTM generally provides improved forecasting accuracy

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/electricity-demand-forecasting-arima-lstm.git