# 📊 Supply Chain Demand Forecasting with Excel & ETS

## 🎯 Project Overview
Time-series forecasting project on **78k+ weekly supply chain records** (3 years, 50 products × 10 regions).  
Implemented **Moving Average, Exponential Smoothing (Solver), and ETS (Holt-Winters)** in Excel to improve forecast accuracy for **demand & inventory planning**.

## 🛠 Tools Used
- Microsoft Excel  
  - Data Cleaning & Preparation  
  - Pivot Tables  
  - Moving Average  
  - Exponential Smoothing (Solver)  
  - ETS (Holt-Winters)  

## 🔍 Approach
1. Collected and cleaned 78k+ weekly supply chain records  
2. Built baseline **Moving Average** model  
3. Applied **Exponential Smoothing** to adjust for recent changes  
4. Applied **ETS (Holt-Winters)** to capture both **trend & seasonality**  
5. Compared accuracy using **MAE, RMSE, and MAPE**  

## 📊 Model Comparison
| Method                | MAE (units) | RMSE   | MAPE (%) | Insights |
|------------------------|-------------|--------|----------|----------|
| Moving Average         | ~5250       | ~19178 | 3.8      | Simple baseline, but lagging effect |
| Exponential Smoothing  | ~2381       | ~3004  | 1.7      | Adjusts to recent changes |
| ETS (Holt-Winters)     | ~2157       | ~2853  | 0.6      | ✅ Best model – captures trend & seasonality |

## ✅ Key Insights
- Demand follows clear seasonal patterns  
- **ETS achieved the lowest forecast error** (MAPE ~0.6%)  
- Results support better **inventory optimization** and **supply chain planning**  

## 📂 Files in this Repository
- `Demand_Forecasting.xlsx` → Data, models & results  
- `forecast_chart.png` → Visualization of forecast *(to be added later)*  

## 👤 Author
Pratik | MBA in Business Analytics & Digital Marketing
