# Neural Network for MNIST Digit Classification

This code demonstrates the implementation of a simple neural network to perform digit classification using the MNIST dataset. The MNIST dataset consists of handwritten digits along with their corresponding labels. The neural network is trained to recognize and classify these digits into the correct labels.

## Note Regarding Errors

Please note that there seem to be some issues in the provided code that are unrelated to the actual implementation of the neural network. These errors appear to be on my end and are related to file paths. 

## Code Overview

1.  **Importing Libraries:** The code begins by importing necessary libraries, including `numpy` for numerical operations, `scipy.special` for the sigmoid function, and `matplotlib.pyplot` for plotting. It also includes a command `%matplotlib inline` to display plots within the notebook.
    
2.  **Neural Network Class Definition:** The `neuralNetwork` class is defined, which represents the structure and behavior of the neural network. It includes methods for initialization, training, and querying the network.
    
3.  **Initializing the Neural Network:** The neural network is initialized with the specified number of input nodes, hidden nodes, output nodes, and learning rate. Weights are initialized using random values.
    
4.  **Loading Training Data:** Training data is loaded from the test file, which contains the MNIST training dataset. Each record in the dataset represents an image of a digit along with its label.
    
5.  **Training the Neural Network:** The code goes through a specified number of epochs and iterates through the training data. It processes each record, scales the inputs, creates target output values, and trains the neural network using the `train` method.
    
6.  **Loading Test Data:** Test data is loaded from a test file, which contains a subset of the MNIST test dataset.
    
7.  **Testing the Neural Network:** The neural network is tested using the test data. The code iterates through the test data, processes each record, queries the neural network for predictions, and compares them to the correct labels. The accuracy of the network's predictions is calculated and printed.

## Final Note
I wrote this code by following the "Make Your Own Neural Network" book, written by Tariq Rashid. In the book, Tariq first explains what a neural network is, how it works, and how to train it. He then goes on to walk through the process of building the neural network using Python.
