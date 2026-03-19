# Coral-Bleaching-Early_Warning-System

##  Project Overview
Coral bleaching is a major environmental issue caused by rising ocean temperatures.
This project aims to analyze oceanographic data and build a machine learning model to understand and predict coral bleaching conditions.

## Objectives

* Analyze ocean temperature variations
* Identify patterns related to coral bleaching
* Build a predictive model using environmental data
* Visualize relationships between key variables
  
## 📊 Dataset Description

This project uses three types of ocean data:

### 🔹 Sea Surface Temperature (SST)

* File: `coraltemp_v3.1_*.nc`
* Represents actual ocean surface temperature

### 🔹 Sea Surface Temperature Anomaly (SSTA)

* File: `ct5km_ssta_v3.1_*.nc`
* Shows deviation from normal temperature

### 🔹 Degree Heating Weeks (DHW)

* File: `ct5km_dhw_v3.1_*.nc`
* Indicates accumulated thermal stress on corals

📁 Data format: NetCDF (`.nc`)

## ⚙️ Technologies Used
* Python
* Pandas
* NumPy
* Xarray
* Matplotlib
* Seaborn
* Scikit-learn

## 📈 Visualizations
📊 SST Distribution
🔥 Correlation Heatmap
📉 SSTA vs SST
🤖 Model Prediction

## 🤖 Machine Learning Model
* Model Used: Random Forest Regressor
* Input Features: SSTA, DHW
* Target Variable: SST

### 📉 Performance

* Mean Squared Error (MSE): 0.261


