﻿# sentiment-analysis

Usage
Data Preparation: Place your dataset in the data/ directory.
Run Notebook: Open and run the sentiment_analysis.ipynb notebook to explore the data, preprocess it, and train the model.
Model Evaluation: Evaluate the performance of the trained model within the notebook.
Notebook Details

The sentiment_analysis.ipynb notebook includes the following steps

    Import Libraries: Import necessary libraries such as NumPy, Pandas, Keras, and Scikit-learn.
    Data Loading: Load the dataset and perform initial exploration.
    Data Preprocessing: Clean the text data using regular expressions, tokenize the text, and pad sequences.
    Model Building: Build a Sequential model using Keras with Embedding, LSTM, and Dense layers.
    Model Training: Split the data into training and testing sets, and train the model using EarlyStopping.
    Model Evaluation: Evaluate the model's performance on the test set.

Dataset
The dataset should be in CSV format with at least two columns: text and sentiment.

Dependencies
numpy
pandas
keras
scikit-learn
tensorflow
