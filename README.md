# GDG-chaitanya

This project implements an end-to-end financial time series forecasting engine using Keras (TensorFlow) and LSTM neural networks, designed specifically to model uncertainty and volatility in market data rather than producing a single point estimate.

The system trains on historical stock data and produces:
- Historical trend visualization
- 7-day forward forecasts
- Shaded confidence intervals (quantile-based)
- Accuracy metrics (RMSE, MAE)
