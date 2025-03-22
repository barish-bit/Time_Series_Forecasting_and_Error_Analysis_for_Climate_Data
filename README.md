# Time Series Forecasting and Error Analysis for Climate Data

This repository contains a 7th-semester academic project focused on **forecasting temperature data** using time series models and analyzing the accuracy and error associated with these models. The project explores **linear prediction**, **exponential smoothing**, and their **averaged ensemble**, applied to climate data from the **Pune-Nagpur region in India**.

---

## 📌 Objective

To understand and implement various time series forecasting methods and analyze their strengths and weaknesses through error metrics, both **categorical** and **quantitative**.

---

## 📊 Models Implemented

1. **Linear Prediction Model**
   - Forecasts using past values (last 3 years for each day).
   - Simple and computationally efficient.
   - Uses MSE for error analysis.

2. **Exponential Smoothing Model**
   - Captures trend and seasonality using weighted averages.
   - Emphasizes recent observations more.
   - Typically more accurate than linear models.

3. **Average Model (Ensemble)**
   - Takes the average of the predictions from both models.
   - Shows improved performance by reducing extreme errors from individual models.

---

## 📈 Error Metrics Analyzed

### 🔵 Quantitative Forecast Metrics:
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **Variance of Observed vs Predicted**
- **Correlation Skill Score**
- **Brier Skill Score**
- **Conditional Probabilities (P(f=x | x=range))**

### 🔴 Categorical Forecast Metrics:
- **Contingency Table (2-Class: Above/Below Average)**
- **Heidke Skill Score (HSS)**

---

## 📂 Project Structure

