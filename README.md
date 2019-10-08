# NeuralNetFromScratchMNIST

This repository contains an example of a simple neural network created with scratch using python. The network was inspired by the book "Make Your Own Neural Network: A Gentle Journey Through the Mathematics of Neural Networks, and Making Your Own Using the Python Computer Language" by Tariq Rashid.

Convert.py takes the following files:

- train-images-idx3-ubyte (Training inputs)
- train-labels-idx1-ubyte (Traning labels)
- t10k-images-idx3-ubyte (Testing inputs)
- t10k-labels-idx1-ubyte (Testing labels)

and extracts the images and the labels for the network to work with. The extracted information is stored in a CSV file for ease of use.

After the extraction has been completed, nn_num_reg_1h.ipynb can be used to solve the MNIST problem. The network used to solve the problem is a simple network with one hidden layer. There are no complex techniques used, there is only feed-forward and back propagation.
