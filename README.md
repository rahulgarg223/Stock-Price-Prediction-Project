#  Stock Price Prediction

This project demonstrates how to predict stock prices using **LSTM (Long Short-Term Memory)** neural networks in TensorFlow/Keras.  
It uses historical stock price data of multiple companies and focuses specifically on **Apple (AAPL)** stock for training and prediction.

---

## Features
- Loads and processes historical stock data (`all_stocks_5yr.csv`).
- Visualizes stock price trends for major tech companies (AAPL, AMD, FB, GOOGL, AMZN, NVDA, EBAY, CSCO, IBM).
- Builds an **LSTM-based deep learning model** to predict stock closing prices.
- Evaluates performance with **MSE (Mean Squared Error)** and **RMSE (Root Mean Squared Error)**.
- Plots actual vs predicted stock prices.

---

##  Project Structure
- stock_price_prediction.py # Main script
- all_stocks_5yr.csv # Dataset (5 years of stock data)
- README.md # Project documentation


---

##  Requirements

Install the following Python libraries before running the project:

```bash
pip install pandas numpy matplotlib seaborn tensorflow scikit-learn

python stock_price_prediction.py


