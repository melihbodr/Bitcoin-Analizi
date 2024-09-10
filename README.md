# Bitcoin Price Prediction with LSTM

## Overview

This project demonstrates the use of Long Short-Term Memory (LSTM) networks for predicting Bitcoin prices. Using historical price data, the model forecasts future values, providing insights for potential investment decisions.

## Features

- **Time Series Forecasting**: Utilizes LSTM, a type of recurrent neural network, to handle time series data effectively.
- **Data Preprocessing**: Includes normalization and preparation of data for training and testing.
- **Visualization**: Displays predicted vs. actual Bitcoin prices through informative plots.

## Setup

1. **Install Dependencies**:
   - TensorFlow
   - NumPy
   - Pandas
   - Matplotlib
   - Scikit-learn

   You can install these libraries via pip:

   ```bash
   pip install tensorflow numpy pandas matplotlib scikit-learn
2. **Data**:
The project requires historical Bitcoin price data in an Excel file. Ensure that the data file (BTC2.xlsx) is properly formatted and accessible.

## Usage

**Data Preparation**: Load and preprocess historical Bitcoin price data.
**Model Training**: Train the LSTM model using historical data.
**Prediction**: Use the trained model to predict future Bitcoin prices.
**Visualization**: Compare predicted prices with actual prices through plots.

## Results
The model provides predictions for future Bitcoin prices and visualizations to compare these predictions with actual historical data. Performance metrics such as the R-squared score are used to evaluate the model's accuracy.
