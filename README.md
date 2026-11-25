# 🧠 Perceptron Learning Algorithm

A from-scratch implementation of the Perceptron Learning Algorithm using Python to understand the fundamental concepts of machine learning and artificial neural networks.

## 📌 Overview

The Perceptron is one of the simplest artificial neural network models used for binary classification. This project demonstrates how a perceptron learns from training data by adjusting its weights and bias based on prediction errors.

The implementation focuses on understanding the mathematical foundations of machine learning, including weighted inputs, bias, activation functions, decision boundaries, and the learning process.

## 🎯 Objectives

- Understand the fundamentals of an artificial neuron.
- Implement the Perceptron Learning Algorithm from scratch.
- Understand weights, bias, and learning rate.
- Implement a threshold-based activation function.
- Learn how a model updates parameters based on prediction errors.
- Understand binary classification and linear decision boundaries.

## ⚙️ How the Perceptron Works

The Perceptron follows these steps:

1. Initialize weights and bias.
2. Calculate the weighted sum of input features.
3. Apply the activation function.
4. Generate a prediction.
5. Calculate the prediction error.
6. Update weights and bias.
7. Repeat the process until the model learns or reaches the maximum number of iterations.

## 🧮 Mathematical Formula

### Weighted Sum

\[
z = w^Tx + b
\]

### Activation Function

\[
\hat{y} =
\begin{cases}
1 & z \geq 0 \\
0 & z < 0
\end{cases}
\]

### Weight Update Rule

\[
w = w + \eta(y-\hat{
