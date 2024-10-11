# NTT Model Training and Prediction

## Overview

This project implements a Long Short-Term Memory (LSTM) model for predicting time series data related to NTT (Nippon Telegraph and Telephone Corporation) stock prices. The model is designed to learn patterns from historical stock data to make future price predictions.

The program performs the following tasks:
1. Data preprocessing (scaling and splitting into training, validation, and test sets).
2. Model building using LSTM layers with hyperparameter tuning.
3. Model training and validation.
4. Saving the trained model and the scaler for future predictions.

## Prerequisites

To run this program, you need the following:
- Python 3.7 or higher
- TensorFlow 2.17.0
- Keras
- scikit-learn
- joblib
- pandas
- matplotlib

You can install the required packages using pip:

```bash
pip install tensorflow==2.17.0 keras scikit-learn joblib pandas matplotlib
