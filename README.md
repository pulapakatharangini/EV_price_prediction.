# EV_price_prediction.
Electric Vehicle (EV) Price Prediction using Machine Learning

# 🔋 Electric Vehicle (EV) Price Prediction using Machine Learning

This project aims to predict the **price of Electric Vehicles (EVs)** based on various specifications such as battery capacity, efficiency, range, top speed, and acceleration.  
The dataset used contains details of 360 EV models from different manufacturers.

## 📁 Project Overview

Electric Vehicles (EVs) are becoming increasingly popular worldwide.  
Accurately predicting their prices based on specifications helps consumers, researchers, and manufacturers understand market trends and value distribution.

This project uses **Python** and **Machine Learning (Regression)** techniques to build a predictive model that estimates the EV price from technical specifications.

## 🧠 Objectives

- Perform **data preprocessing** and **feature scaling**
- Build a **regression model** (Linear Regression baseline)
- Evaluate model performance using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score
- Provide insights into factors influencing EV price

## 📊 Dataset

**File name:** `EV_cars.csv`  
**Number of records:** 360  
**Main columns:**
- `Battery` – Battery capacity (kWh)
- `Efficiency` – Energy efficiency (Wh/km)
- `Fast_charge` – Fast charging capability (kW)
- `Range` – Maximum range (km)
- `Top_speed` – Maximum speed (km/h)
- `acceleration..0.100.` – 0–100 km/h acceleration (seconds)
- `Price.DE.` – Price (Target Variable)

## 🧩 Technologies Used

- **Python 3**
- **pandas**, **NumPy** – Data handling  
- **scikit-learn** – Model building and evaluation  
- **matplotlib / seaborn** (optional) – Data visualization
