Simple Neural Network for Odd/Even Number Prediction
This repository contains a simple implementation of a neural network using Python and the NumPy library to predict whether a given number is odd or even. The neural network uses a single input and a single hidden layer with sigmoid activation functions.

Requirements
Python 3.x
NumPy
How to Use
Make sure you have Python 3.x and NumPy installed on your system.
Download or clone this repository to your local machine.
Code Overview
The neural network consists of the following components:

1. Activation Function
The sigmoid function is defined to introduce non-linearity into the neural network. It maps any input to a value between 0 and 1.

2. SimpleNeuralNetwork Class
The SimpleNeuralNetwork class is the core of the neural network. It has the following attributes:

input_weights: Randomly initialized weights for the input layer.
hidden_weights: Randomly initialized weights for the hidden layer.
The class has the following methods:

__init__(): Initializes the neural network with random weights for both layers.
predict(x): Performs a forward pass through the neural network and returns the output prediction for the given input x.
3. Training the Model
The neural network is trained on a set of labeled data consisting of integers and their corresponding labels (0 for even, 1 for odd). The training process involves the following steps:

Forward pass through the neural network to obtain predictions.
Calculation of the prediction error.
Backpropagation of the error to adjust the weights of both layers.
4. Testing the Model
After training the model, it can predict whether a given number is odd or even. We use the model's predict() method to make predictions on new data and display the results.

Training the Model
To train the model, modify the data and labels arrays in the code to include your training data. You can adjust the number of training epochs and the learning rate to fine-tune the model's performance.

Testing the Model
To test the model, modify the test_data array in the code to include the numbers you want to test. The model will make predictions for each input and display the results.

Disclaimer
This is a basic implementation of a neural network and may not perform well on complex tasks. For more complex problems, consider using larger networks, different activation functions, and advanced optimization techniques.

Credits
This implementation was created by [Your Name] as a part of a learning project. Feel free to use, modify, and distribute it according to the terms of the license.
