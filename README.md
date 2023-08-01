# Stock Price Prediction with LSTM
In this example, we use LSTM (Long Short-Term Memory), a type of Recurrent Neural Network (RNN), to predict stock prices. LSTM networks are well-suited to making predictions based on time series data because they can understand the context and trends in sequential input by having hidden states.

## Data
The data file used in this script is `AMZN.csv`, which contains daily stock price data for Amazon (AMZN). We specifically use the `Date` and `Close` price for each day.

## Code Explanation
This script predicts stock prices using an LSTM (Long Short-Term Memory) model implemented with PyTorch. It first imports necessary libraries and loads Amazon's historical stock price data from a CSV file. After preprocessing the data, which includes dropping irrelevant columns, converting dates, and scaling values, it prepares the data for LSTM and splits it into training and test sets. The LSTM model is defined and trained with the training data, with hyperparameters set beforehand. After training, the model predicts stock prices for the test set, and the prediction's accuracy is evaluated using Mean Squared Error.

Note: Before running this script, make sure that the file 'AMZN.csv' is in the same directory as the script.

[Code](Amazon_Stock_Forecasting_with_LSTM.ipynb)

## License

This script is open-source and licensed under the MIT License. For more details, check the [LICENSE](LICENSE) file.
