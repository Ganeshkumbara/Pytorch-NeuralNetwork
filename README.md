# Pytorch-NeuralNetwork

# Objective 1: Train a simple MLP neural network to classify (3-class) the 4-dimension dataset cluster 
  ![image](https://github.com/user-attachments/assets/d5a6bac0-6379-4ae0-87e3-33d80b317328)

## Neural Network
  * Defining your neural network architecture
  * Initializing your optimizer and loss function
  * Looping over your number of training epochs
  * Looping over data batches inside each epoch
  * Making predictions and computing the loss on the current batch of data
  * Zeroing out your gradient
  * Performing backpropagation
  * Telling your optimizer to update the gradients of your network
  * Telling PyTorch to train your network with a GPU (if a GPU is available on your machine, of course)

## Multilayer Preceptron (MLP)
  A Multilayer Perceptron (MLP) is a type of artificial neural network that consists of multiple layers of nodes (neurons). Here's a breakdown of its key features:

  * Architecture: MLPs have an input layer, one or more hidden layers, and an output layer. Each layer is fully connected to the next one, meaning every neuron in one layer is connected to every       neuron in the following layer.
  * Activation Functions: Neurons in MLPs use activation functions (like ReLU, sigmoid, or tanh) to introduce non-linearity into the model, allowing it to learn complex patterns.
  * Feedforward Process: Data flows in one direction—from the input layer through the hidden layers to the output layer—without any cycles or loops.
  * Backpropagation: MLPs are trained using a method called backpropagation, which adjusts the weights of connections based on the error of the output compared to the expected result.
  * Applications: MLPs are used for various tasks, including classification, regression, and function approximation in fields like image recognition, natural language processing, and more.

# PyTorch: Training a Convolutional Neural Network (CNN)
