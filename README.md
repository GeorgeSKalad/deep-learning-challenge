# deep-learning-challenge



# Charity ML Neural Network Project

## Overview

This project involves building and training a neural network model to predict whether applicants for charitable donations from Alphabet Soup will be successful. The model uses data from the `charity_data.csv` dataset, preprocesses the data, and then trains a neural network to make predictions. This README file provides an overview of the project and instructions for running the code.

## Dependencies

Before running the code, ensure you have the following dependencies installed:

- scikit-learn
- pandas
- TensorFlow




## Preprocessing the Data

In the code, we perform the following preprocessing steps:

- Drop non-beneficial ID columns (`EIN` and `NAME`).
- Binning of values in the `APPLICATION_TYPE` and `CLASSIFICATION` columns.
- Convert categorical data to numeric using one-hot encoding.
- Split the data into training and testing datasets.
- Standardize the features using `StandardScaler`.

## Building and Training the Neural Network

We build a 3 neural network models with the following architecture:

- Input layer with the number of input features determined by the dataset.
-  hidden layers with ReLU activation functions.
-  hidden layers with sigmoid activation functions.
- Output layer with a sigmoid activation function for binary classification.

We compile the model using binary cross-entropy loss and the Adam optimizer and train it for 100 epochs.

## Evaluating each Model

We evaluate the model's performance using the test dataset and print the loss and accuracy.

## Saving each Model

The trained model is saved in an HDF5 file named `AlphabetSoupCharity.h5`,'AlphabetSoupCharity2.h5`and 'AlphabetSoupCharity3.h5`


## In this challenge  resources been utilized 
online research, online resources , tutor assistances .


