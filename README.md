# Next-word-prediction
prediction of words you're about to type using LSTM RNN (long short term memory recurring neural network) + recurring neural networks


# Word Prediction with LSTM RNN (Long Short Term Memory)



## Overview

This project demonstrates word prediction using **LSTM (Long Short Term Memory)** networks, a type of **Recurrent Neural Network (RNN)**. The model is trained on a dataset of text, and can predict the next word based on the context of previously typed words. This application showcases the power of sequence models, specifically LSTMs, in handling and predicting natural language sequences.

## Features

- Predicts the next word based on a given context.
- Utilizes an LSTM RNN architecture for effective learning of sequential data.
- Trained on large corpora of text for improved prediction accuracy.
- Interactive demo to showcase word prediction in real-time.

## Technologies Used

- **Python**
- **TensorFlow** for deep learning model training.
- **Keras** for building and training the LSTM RNN model.
- **Matplotlib** for visualizing model performance.
- **Pandas** for data manipulation.

## Model Architecture

The model is built using **LSTM** (Long Short Term Memory), a type of **RNN (Recurrent Neural Network)**, that is particularly well-suited for sequential data like text. The architecture consists of:

- **Embedding Layer**: Converts words into dense vectors of fixed size.
- **LSTM Layer(s)**: Learns long-term dependencies between words.
- **Dense Layer**: Outputs the prediction for the next word.



