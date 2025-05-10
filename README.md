# Stock Market Trend Prediction using LSTM 

This project uses Long Short-Term Memory (LSTM) neural networks to predict Apple (AAPL) stock prices using both daily and 1-minute intraday data. The model outputs predictions, evaluates accuracy, and flags strong buy signals when both timeframes agree.

The models are trained on real stock market data and combined to simulate intelligent trading signals (BUY / SELL / HOLD).  
Evaluation metrics, visualizations, and signal logic are included to assess performance and support decision-making.

## Project Structure

- `stock_market_trend_using_LSTM.ipynb`: Main notebook for data preprocessing, training, and prediction.
- `min_predictions_aapl.csv`: Rescaled 1-minute prediction for Apple Inc. stock
- `daily_predictions_aapl.csv`: Rescaled daily prediction for Apple Inc. stock 
- `model_predictions_log.csv`: Combined prediction log for both models.
- `requirements.txt`: Python dependencies required to run the project.

## Features

- Two LSTM models: one for daily and one for intraday price predictions.
- Real-time 1-minute data via Alpha Vantage.
- Evaluation metrics: MAE, RMSE, and MAPE.
- Decision logic to flag **"Strong Buy Signal"** if both models predict upward movement.

## Usage

1. Clone the repo and install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

2. Set your Alpha Vantage API key in a `.env` file:
    ```
    ALPHA_VANTAGE_API_KEY=your_key_here
    ```

3. Run the notebook: `stock_market_trend_using_LSTM.ipynb`

---

**Author:** Tam Tran  
**Institution:** Cal Poly Pomona  
**Date:** May 2025  
**Goal:** To build and evaluate AI-based forecasting models for intelligent stock market trend prediction using deep learning.

---
