# 🚦 IoT Time Series Forecasting for Smart Cities  

## 📝 Project Overview
Urban mobility is becoming increasingly complex, with growing populations leading to **traffic congestion, delays, inefficiency, and higher emissions**.  
This project addresses these challenges by using **IoT sensor data** and **time series forecasting techniques** to predict **hourly vehicle traffic at major intersections**.  

📌 By anticipating traffic volumes, city authorities can:  
- Plan proactively and optimize infrastructure usage  
- Reduce congestion and CO₂ emissions  
- Improve the quality of life for citizens  

---

## 🎯 Key Highlights
- ✅ Forecasted **hourly traffic volume** at 4 major city junctions  
- ✅ Designed a **data pipeline**: cleaning, anomaly detection, feature engineering  
- ✅ Built a **hybrid predictive model**: Regression (trend + seasonality) + ARIMA/SARIMA  
- ✅ Performed **residual analysis** (stationarity, ACF/PACF) to validate models  
- ✅ Delivered **visual insights** into traffic peaks, seasonalities, and patterns  

---

## 📊 Dataset
- **Source**: IoT traffic sensors  
- **Period**: Nov 2015 – Jun 2017  
- **Size**: ~48,120 hourly observations across 4 intersections  
- **Main Features**:  
  - `DateTime` → timestamp (hourly)  
  - `Junction` → intersection ID (1–4)  
  - `Vehicles` → number of vehicles per hour  
  - `ID` → record identifier  

---

## 🔧 Workflow
Data ingestion & cleaning
└─ Removal of duplicates, missing values, outliers

Exploratory Data Analysis (EDA)
└─ Visualizing trends, seasonalities, and anomalies

Feature Engineering
└─ Time-based variables, sinusoidal seasonal components

Modeling
└─ Regression models (trend + seasonality)
└─ ARIMA/SARIMA applied to residuals

Validation
└─ Residual diagnostics (ACF, PACF, stationarity tests)

Forecasting & Visualization
└─ Generate predictions + compare against real values



---

## 📈 Results & Impact
- 📉 **Reduced prediction error** by combining regression + SARIMA  
- 📊 Identified **daily & weekly seasonal patterns** in traffic  
- 🏙️ Provides a **decision support tool** for smart city planners  
- 🌍 Contributes to **SDGs**:  
  - **SDG 11**: Sustainable Cities & Communities  
  - **SDG 9**: Innovation & Infrastructure  
  - **SDG 13**: Climate Action  

---

## 🛠️ Tech Stack
- **Language**: Python  
- **Libraries**:  
  - Data Processing → `pandas`, `numpy`  
  - Visualization → `matplotlib`, `seaborn`  
  - Time Series Forecasting → `statsmodels` (ARIMA, SARIMA), `scikit-learn`  



---

## 🚀 What I Learned
- Building **end-to-end machine learning pipelines** for time series forecasting  
- Applying **statistical models (SARIMA)** alongside regression for improved accuracy  
- Handling **real-world IoT data challenges** (missing values, anomalies, irregularities)  
- Translating **technical models into business insights** for urban planning  

---

💼 This project demonstrates skills in **time series forecasting, data preprocessing, model validation, and real-world impact analytics**.  
