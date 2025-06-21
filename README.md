# StockCast – LSTM-based Google Stock Price Prediction

## Project Overview
StockCast is a deep learning project that predicts Google (GOOG) stock prices using historical market data from Yahoo Finance. The model leverages Long Short-Term Memory (LSTM) neural networks to analyze time-series data and forecast future closing prices. 

The project involves:
- Downloading and preprocessing 10 years of stock price data.
- Visualizing trends using moving averages.
- Building and training a multi-layer LSTM model with dropout for regularization.
- Predicting stock prices and visualizing results against actual prices.

## Features
- Data collection via Yahoo Finance API
- Data preprocessing including scaling and sliding window creation
- Visualization of stock closing prices and moving averages
- Multi-layer LSTM neural network for time series forecasting
- Prediction visualization comparing predicted vs. real stock prices
- Model saving for future inference or retraining

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- scikit-learn
- TensorFlow & Keras
- yfinance API

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/StockCast.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter notebook (`StockCast.ipynb`) in VS Code or JupyterLab.

## Notes
- The model uses 100 days of historical data to predict the next day’s closing price.
- Ensure an active internet connection for downloading stock data.
- The model is trained on data from 2012 to 2022.

## License
This project is open source and available under the MIT License.

---

*Feel free to contribute or raise issues!*
