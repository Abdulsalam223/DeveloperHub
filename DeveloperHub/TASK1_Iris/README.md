# 📈 Short-Term Stock Price Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on **predicting the next day’s closing stock price** using historical market data.  
The goal is to demonstrate how machine learning regression models can be applied to financial time-series data for **short-term forecasting**.

Historical stock data is retrieved from **Yahoo Finance** using the `yfinance` Python library, and features such as **Open, High, Low, and Volume** are used to predict the **next day’s Close price**.

---

## 🎯 Objective
- Retrieve historical stock market data
- Perform feature engineering for next-day prediction
- Train a regression-based machine learning model
- Evaluate model performance
- Visualize actual vs predicted stock prices

---

## 📊 Dataset
- **Source:** Yahoo Finance  
- **Library Used:** `yfinance`
- **Stock Selected:** Apple Inc. (AAPL)
- **Time Range:** 2018 – 2024

### Features Used
| Feature | Description |
|------|------------|
| Open | Opening price of the day |
| High | Highest price of the day |
| Low | Lowest price of the day |
| Volume | Number of shares traded |
| Close | Closing price (used to create target) |

### Target Variable
- **Next_Close:** Closing price of the following trading day

---

## 🛠️ Technologies Used
- Python
- pandas
- numpy
- matplotlib
- yfinance
- scikit-learn

---

## 🧠 Machine Learning Models
- **Linear Regression** (Primary model)
- **Random Forest Regressor** (Optional enhancement)

---

## ⚙️ Methodology
1. Download historical stock data using Yahoo Finance
2. Select relevant financial features
3. Shift closing price to create next-day prediction target
4. Split data into training and testing sets (time-series aware)
5. Train regression model
6. Evaluate model performance
7. Visualize actual vs predicted prices

---

## 📈 Model Evaluation Metrics
The model is evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help assess prediction accuracy and model reliability.

---

## 📉 Visualization
A line plot is used to compare:
- **Actual closing prices**
- **Predicted closing prices**

This visualization helps understand how closely the model follows real market trends.

---

## 🔍 Key Observations
- Short-term price movements can be reasonably approximated using intraday features
- High and Low prices tend to have the strongest influence on next-day closing prices
- Linear Regression provides a simple and interpretable baseline model

---

## 🚀 How to Run the Project

### 1️⃣ Install Dependencies
```bash
pip install yfinance pandas numpy matplotlib scikit-learn
