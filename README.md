# Stock Price Prediction using LSTM (AAPL)

This project implements a Deep Learning model using Long Short-Term Memory (LSTM) networks to predict stock prices of Apple Inc. (AAPL).

---

##  Project Overview

Stock market prediction is a challenging time-series forecasting problem.  
In this project, we use historical stock price data of Apple (AAPL) and apply an LSTM neural network to predict future closing prices.

The model is evaluated using RMSE and MAE metrics to measure prediction accuracy.

---

##  Company Details

- Company: Apple Inc.
- Ticker Symbol: AAPL
- Exchange: NASDAQ
- Data Source: Yahoo Finance (yfinance)

---

## Technologies Used

- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- yfinance

---

##  Data Preprocessing

- Downloaded historical stock data
- Selected "Close" price for prediction
- Normalized data using MinMaxScaler
- Created 60-day time-step sequences
- Split data into Training (80%) and Testing (20%)

---

##  Model Architecture

- LSTM Layer (with multiple units)
- Dropout Layer (to reduce overfitting)
- Dense Output Layer
- Optimizer: Adam
- Loss Function: Mean Squared Error (MSE)

---

## Model Evaluation

The model performance was evaluated using:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

The prediction graph shows that the model closely follows the actual stock price trend.

---

##  Results

- Successfully captured time-series patterns
- Reasonable RMSE and MAE values
- Good alignment between predicted and actual prices

(Add your prediction graph screenshot here)

---

##  Future Improvements

- Add technical indicators (RSI, MACD)
- Multi-stock prediction
- Hyperparameter tuning
- Deploy using Streamlit web app
- Compare with GRU model

---

##  How to Run

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/yourrepo.git
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```
   jupyter notebook
   ```

---

##  Conclusion

This project demonstrates the application of LSTM networks for financial time-series forecasting and showcases practical implementation of deep learning in stock market prediction.
