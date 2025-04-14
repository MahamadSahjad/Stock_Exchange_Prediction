# 📈 Zomato Stock Price Prediction

This project focuses on predicting the future stock prices of **Zomato Ltd.** using historical data and machine learning techniques. The goal is to assist investors and analysts in understanding potential future trends based on past stock performance.

---

## 📌 Table of Contents

- [Objective](#objective)
- [Libraries Used](#libraries-used)
- [Workflow](#workflow)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)

---

## 🎯 Objective

To use historical stock data to build a machine learning model that can predict future closing prices of **Zomato stock** listed on the NSE (ticker: `ZOMATO.NS`).

---

## 🧰 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `yfinance`
- `sklearn` (for machine learning and model evaluation)

---

## 🔁 Workflow

### 1. Data Collection
- Historical stock data for Zomato is collected using the `yfinance` API.
- Features include: `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`.

### 2. Exploratory Data Analysis (EDA)
- Visualize stock trends using line plots.
- Analyze volatility using moving averages.
- Distribution and trend insights via Seaborn plots.

### 3. Feature Engineering
- Generate new features such as:
  - 100-day and 200-day Moving Averages
  - Daily Returns
  - Lag features

### 4. Data Preprocessing
- Split data into training and testing sets.
- Normalize using MinMaxScaler.
- Define features and target variable (`Close`).

### 5. Model Building
- Applied **Linear Regression** to predict future prices.
- Trained on historical data and tested on recent values.

### 6. Model Evaluation
- Used metrics like:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- Visual comparison of actual vs predicted prices.

---

## 📊 Results

- The Linear Regression model captures the overall trend but has limitations in handling volatility and sharp movements.
- Prediction accuracy can be improved using advanced models.

---

## ✅ Conclusion

This project successfully demonstrates how historical financial data can be used to forecast stock prices using machine learning. While the current model serves as a strong baseline, it opens the door for future improvements with more sophisticated techniques.

---

## 🚀 Future Work

- Implement LSTM (Long Short-Term Memory) neural networks for time-series prediction.
- Explore models like ARIMA, XGBoost, and Random Forests.
- Incorporate external features (e.g., news sentiment, macroeconomic data).
- Create a real-time stock price dashboard.

---

## 📂 File Structure

