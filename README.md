# Stock Price Prediction using LSTM

This project focuses on predicting the stock prices of Apple Inc. (AAPL) using Long Short-Term Memory (LSTM) networks. LSTM is a type of recurrent neural network (RNN) well-suited for sequence prediction tasks due to its ability to retain information over long periods. The dataset utilized for training and testing the model is obtained from the Tiingo API through the pandas_datareader library.

## Requirements

- Python 3.x
- pandas
- pandas_datareader
- numpy
- matplotlib
- scikit-learn
- TensorFlow 2.x
- Keras

## Installation

- Obtain Tiingo API key:
- Fetches historical stock data of Apple Inc. using Tiingo API.
- Preprocesses the data, including scaling using MinMaxScaler.
- Builds an LSTM model for stock price prediction.
- Trains the model on the training data.
- Evaluates the model's performance on the test data.
- Predicts stock prices for the next 30 days.
- Plots the actual stock prices vs. predicted stock prices.

## Results
The LSTM model demonstrates promising results in predicting the stock prices of Apple Inc. The predicted prices closely track the actual prices, suggesting the effectiveness of the model in capturing underlying patterns in the stock data.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgement
We would like to express our gratitude to Tiingo for providing the financial data necessary for this project.
