# Backpropagation of Logistic Regression

## Overview

This project implements the backpropagation algorithm for training a **logistic regression** model. Logistic regression is a widely-used algorithm for binary classification problems, and backpropagation is a key optimization technique for training machine learning models by adjusting model parameters to minimize the loss function.

The primary objective of this project was to understand and implement the mechanics of the backpropagation algorithm from scratch and apply it to train a logistic regression model on a binary classification dataset.

## Key Concepts

- **Logistic Regression**: A linear classifier used for binary classification, which predicts the probability of one class based on the logistic function (sigmoid) applied to the linear combination of input features.
  
- **Backpropagation**: A supervised learning algorithm used to update the weights of a neural network or model, by computing the gradient of the loss function with respect to each weight using the chain rule. In the context of logistic regression, backpropagation is used to minimize the cost function (cross-entropy loss).

- **Gradient Descent**: An optimization method used to minimize the cost function by iteratively adjusting the weights in the direction of the negative gradient.

## Steps in Implementation

1. **Logistic Regression Model**: I implemented the sigmoid activation function and the cost function (cross-entropy) used in logistic regression.
2. **Forward Propagation**: Calculated the output of the logistic regression model by applying the sigmoid function to the weighted sum of inputs.
3. **Loss Calculation**: Computed the binary cross-entropy loss between the predicted output and actual labels.
4. **Backpropagation**: Used the chain rule to compute the gradients of the weights with respect to the loss and updated the weights using gradient descent.
5. **Training**: The model was trained on a binary classification dataset, and the performance was evaluated using metrics such as accuracy.

## Files Included

- `logistic_regression.py`: Contains the implementation of the logistic regression model, forward propagation, cost function, and backpropagation.
- `train.py`: Script for training the model on a sample dataset.
- `README.md`: Documentation for the project.
