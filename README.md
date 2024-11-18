# Time-Series Forecasting for Different Stock Prices

## Overview
This project provides time-series forecasting of stock prices and some other miscellaneous forecasting. It incorporates data processing, some feature engineering, and machine learning techniques to predict future stock prices based on historical trends.

### Key Components:
1. **Data Processing:**
   - Loading historical stock data from CSV files (primarily Tesla Stock data).
   - Feature engineering to calculate technical indicators such as moving averages.

2. **Machine Learning:**
    - A Long Short-Term Memory (LSTM) model implemented in Tensorflow to predict future stock prices.
    - Predicts future stock prices using a sequence-to-value forecasting approach.
    - Customizable hyperparameters:
      - Sequence length
      - Number of hidden layers
      - Learning rate
      - Batch size
    - Trains efficiently with GPU acceleration.

3. **Forecast Evaluation:**
   - Evaluate the quality of predictions using metrics such as Mean Squared Error (MSE).

---
### Univariate Forecasting:

<img width="951" alt="Skärmavbild 2024-11-18 kl  21 07 17" src="https://github.com/user-attachments/assets/bb91bf67-e1b4-4052-858d-3982a84de514">

---
### Anomaly Detection:

<img width="917" alt="Skärmavbild 2024-11-18 kl  21 07 42" src="https://github.com/user-attachments/assets/4818efef-40ac-4b2f-91ed-45f5946a696e">


