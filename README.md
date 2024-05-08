# Bitcoin Price Prediction Project

## Description
This project aims to predict Bitcoin prices using various statistical and machine learning methods, including Long Short-Term Memory (LSTM) networks with PyTorch, Seasonal ARIMA (SARIMA), and ARIMA models. The purpose is to compare these approaches based on their forecasting accuracy and to determine which method is most suitable for predicting Bitcoin prices under different market conditions.

## Models
- **LSTM with PyTorch**: Implemented in `lstm_model.ipynb` in the `notebooks/` directory, this model uses deep learning to predict future Bitcoin prices based on sequences of past data.
- **SARIMA**: Implemented in `sarima_model.ipynb` in the `notebooks/` directory, this statistical model addresses both seasonal and non-seasonal components of Bitcoin price movements.
- **ARIMA**: Found in `sarima_model.ipynb` in the `notebooks/` directory, focuses on the non-seasonal patterns in Bitcoin price data.

## Results
Each model's performance is evaluated and compared based on RMSE metrics. Results are detailed in `results.md` with accompanying plots in the `plots/` directory.
