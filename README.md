# 📈 Apple Stock Price Prediction

This project uses **historical stock data** of Apple Inc. (AAPL) to **predict the next day's closing price** using machine learning models (Linear Regression and Random Forest).

---

## 🚀 Objective

- Fetch real-time Apple stock data using the `yfinance` API.
- Train ML models to predict future stock prices.
- Visualize actual vs predicted results.
- Evaluate model performance using R² Score and Mean Squared Error (MSE).

---

## 🗃️ Dataset

- Source: [Yahoo Finance](https://finance.yahoo.com/)
- Retrieved using: `yfinance` Python library
- Features used:
  - `Open`, `High`, `Low`, `Volume` ➝ to predict `Close` price

---

## 🧠 Models Used

- **Linear Regression**
- **Random Forest Regressor**

---

## 🛠️ Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
