# stock-target-prediction
# Stock Target Prediction using Linear Regression

This project implements a machine learning model to predict stock **target prices** using **minute-level trade and quote (TAQ) data**. The model uses features like Open, Closed prices, Volume, and more, and applies **Linear Regression** to forecast the target value.

## 📌 Project Overview

- 📈 **Goal**: Predict the target variable (e.g., next price movement or smoothed value) using real-time stock trade and quote data.
- 🧠 **Model Used**: Linear Regression
- 📊 **Data Granularity**: Aggregated to 1-minute intervals
- 🧹 **Preprocessing**: Feature selection, standardization
- ✅ **Evaluation Metric**: Root Mean Squared Error (RMSE)

## 🔍 Features Used

The following features were selected based on correlation analysis:
- `Closed`
- `Totaltradecount`
- `Heigh`
- `Open`

**Target**: A numerical value derived from stock price movement

## 🧪 Results

- ✅ **RMSE**: ~1.53 (on standardized scale)
- 📉 True vs Predicted values plotted to assess performance
- ✅ Performance is considered *moderate*, depending on context and noise in data

## 🛠️ Tools and Libraries

- Python
- Pandas & NumPy
- Matplotlib
- Scikit-learn (for modeling and evaluation)

## 📂 File Structure
