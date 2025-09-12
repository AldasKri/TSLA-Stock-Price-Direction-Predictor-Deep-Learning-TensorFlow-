# TSLA-Stock-Price-Direction-Predictor-Deep-Learning-TensorFlow-

The purpose of this project, like the Youtube View Predictor is an opportunity for me to learn the machine learning and deep learning programs. 

NOTE: This project is for learning purposes only. It is not investment advice. You can lose your money in the stock market. I am not a financial advisor. 

Dataset: Tesla stock data from 2010 to 2020 with columns open, high, low, close, adj close and volume (sourced from Kaggle)

This project applies a TensorFlow deep learning model to predict whether Tesla’s stock price will go up or down compared to the previous day’s close.

Approach:
* Preprocessing with train/validation split and MinMax scaling
* TensorFlow/Keras deep learning model with binary classification (sigmoid output)
* Evaluation with confusion matrix & classification report


Results:
* Validation accuracy: ~82%
* Validation loss: ~0.43
* Balanced performance across both classes (Precision/Recall/F1 ≈ 0.82 for “up” and “down”)

Future Direction - CNN DL model to identify different types of brain tumors from MRI scans (I completed it! Check it out in my repositories)
