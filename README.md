# Stock-price-prediction-using-Neural-networks
# Stock Price Prediction Using CNN-LSTM Hybrid Model

This repository contains a stock price prediction model using a hybrid Convolutional Neural Network (CNN) and Long Short-Term Memory (LSTM) network. The model is designed to predict the stock prices of companies based on historical stock price data, incorporating both short-term and long-term dependencies in the market.

## Project Overview

Stock price prediction is a challenging task in finance, where forecasting future trends can have significant financial implications. This project focuses on predicting the stock prices of **Tesla** using a **CNN-LSTM hybrid model**, which combines the strengths of Convolutional Neural Networks for feature extraction and LSTMs for sequential data modeling.

## Key Features:
- **Hybrid CNN-LSTM Architecture**: Combines the feature extraction capabilities of CNNs with the sequential memory capabilities of LSTMs for better prediction performance.
- **Data Preprocessing**: Includes handling missing data, normalization, and feature engineering.
- **Model Evaluation**: Performance evaluated using common metrics such as MSE, RMSE, MAE, and MAPE.

## Technologies Used

- **Python**: Main programming language used for model development.
- **TensorFlow/Keras**: For building and training the CNN-LSTM model.
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib/Seaborn**: For visualizing training results and stock price predictions.
- **Scikit-learn**: For performance evaluation and model validation.

## Installation Instructions

To run this project locally, clone the repository and install the required dependencies:

```bash
# Clone the repository
git clone https://github.com/yourusername/stock-price-prediction.git

# Navigate to the project directory
cd stock-price-prediction

# Install required libraries
pip install -r requirements.txt
