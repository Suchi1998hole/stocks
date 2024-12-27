# Stock Price Prediction using LSTM

This project implements a Long Short-Term Memory (LSTM) neural network to predict stock prices Example: for Google (GOOG). The model uses historical stock data to forecast future prices.

## Project Structure

The project consists of the following main components:

1. Data Collection
2. Data Preprocessing
3. Model Architecture
4. Training
5. Prediction and Evaluation

## Requirements

- Python 3.x
- TensorFlow
- Keras
- yfinance
- pandas
- numpy
- matplotlib

## Installation

To install the required packages, run:

```bash
pip install tensorflow yfinance keras pandas numpy matplotlib
```

## Usage

1. Data Collection:
   - The script uses yfinance to download historical stock data for the past 20 years.

2. Data Preprocessing:
   - The closing prices are extracted and normalized using MinMaxScaler.
   - The data is then split into training and testing sets.

3. Model Architecture:
   - The LSTM model consists of two LSTM layers followed by two Dense layers.

4. Training:
   - The model is trained on the preprocessed data.

5. Prediction and Evaluation:
   - The trained model is used to make predictions on the test set.
   - The Root Mean Square Error (RMSE) is calculated to evaluate the model's performance.

## Results

The model achieves an RMSE of approximately 6.05, indicating the average deviation of predictions from actual stock prices.

## Future Improvements

- Experiment with different model architectures and hyperparameters.
- Incorporate additional features such as volume, moving averages, or sentiment analysis.
- Implement real-time predictions using the latest market data.

## Disclaimer

This project is for educational purposes only. Stock market predictions are inherently uncertain, and this model should not be used for actual trading decisions without proper risk assessment.
