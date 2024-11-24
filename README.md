MNIST Handwritten Digit Classification Using Keras
This project demonstrates the implementation of a neural network for handwritten digit classification using the MNIST dataset. The MNIST dataset is a popular dataset in the machine learning community, containing 60,000 training images and 10,000 test images of handwritten digits (0-9). The goal is to correctly classify the digits based on the input images.

Table of Contents
Overview
Dataset
Model Architecture
Requirements
Setup and Usage
Results
License
Overview
In this project:

A fully connected neural network (Dense layers) is implemented using Keras.
The model is trained on the MNIST dataset to achieve high accuracy in recognizing handwritten digits.
The implementation highlights preprocessing, training, evaluation, and visualization of results.
Dataset
The MNIST dataset contains:

Training data: 60,000 grayscale images of size 28x28 pixels.
Test data: 10,000 grayscale images of the same size.
Each image is labeled with the corresponding digit it represents (0-9). The dataset is included in Keras and can be loaded directly.

Model Architecture
The implemented neural network consists of:

Input Layer: Accepts the 28x28 pixel images, flattened into a vector of size 784.
Hidden Layers: Fully connected layers with ReLU activation functions for non-linearity.
Output Layer: A softmax layer with 10 nodes, representing the probabilities for each digit (0-9).
Summary
Loss Function: Categorical Crossentropy
Optimizer: RmsProp
Metrics: Accuracy
