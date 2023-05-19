# Convolutional_Neural_Network
"This Python script implements a Convolutional Neural Network (CNN) using Keras for image classification. It includes layers for convolution, pooling, flattening, and dense connections, compiled with the Adam optimizer and trained on image datasets."

This repository contains a Python script that demonstrates the implementation of a Convolutional Neural Network (CNN) using the TensorFlow and Keras libraries.

## Code Description

The `cnn.py` file is a Python script that builds and trains a CNN model for image classification. Here is a breakdown of the code:

1. The script imports the necessary libraries and packages, including TensorFlow and Keras 
2. It initializes the CNN model using the Sequential class from Keras.
3. The script defines the layers of the CNN, including convolutional layers, pooling layers, and fully connected layers.
4. It compiles the model with the Adam optimizer, binary cross-entropy loss function, and accuracy metric.
5. The script uses the ImageDataGenerator class from Keras to preprocess and augment the training and test data .
6. It fits the model to the training data and evaluates its performance on the test data.
