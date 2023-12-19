
# Google Stock Price Prediction using LSTM

## Overview
This repository contains a machine learning project focused on predicting Google's stock prices. The project is based on a [Kaggle notebook](https://www.kaggle.com/code/saikiranreddyk/notebookfeb0b8ce01?scriptVersionId=155641631), utilizing a Long Short-Term Memory (LSTM) network, a type of Recurrent Neural Network (RNN) effective for time series forecasting.

## Data
The model is trained on historical stock price data of Google (GOOG), available from the [Google Stock Price dataset on Kaggle](https://www.kaggle.com/datasets/henryshan/google-stock-price). The dataset includes features such as Open, High, Low, Close, Adjusted Close, and Volume, spanning several years.

## Methodology
- **Data Preprocessing**: Preprocessing includes normalization using `MinMaxScaler` to scale the feature data and creating time-sequenced data batches.
- **LSTM Model**: The model, built using LSTM layers followed by a dense layer, is trained to predict the closing stock prices.
- **Evaluation**: Performance is evaluated using the Root Mean Squared Error (RMSE) metric.

## Results
- The model achieved an RMSE of 111.24 on the test dataset.
- Future improvements may include further model tuning and exploration of feature engineering techniques.

## Technologies Used
- Python
- TensorFlow and Keras for LSTM model building and training
- Pandas and NumPy for data manipulation
- Scikit-learn for data preprocessing

## Usage
Follow the instructions in the repository to replicate the analysis, including data preprocessing, model training, and performance evaluation.

## Contributions
Contributions are welcome, including improvements to the model, experiments with different architectures, or better feature engineering techniques.

## License
The code in this project is released under the [MIT License](https://opensource.org/licenses/MIT). Note that this license does not cover the dataset, which is sourced from Kaggle and subject to Kaggle's terms and conditions.
