# AutoEncoder_Training

This is a simple implementation of an AutoEncoder in Python without using the built-in functionality. AutoEncoders are a type of neural network used for unsupervised learning, particularly for dimensionality reduction. This implementation allows you to create and train an AutoEncoder.

## Parameters
 hiddenlayer_units: Number of units in the hidden layer of the AutoEncoder. (Dimension to which you need to reduce the input data)
 
 learning_rate: Learning rate for updating the weights during training.
 
 dimension: Tuple representing the input dimension of the AutoEncoder. ( Dimension of your data)
 
 epochs: Number of training epochs. ( Number of Epochs using which you need to train the Auto Encoder) 

## Methods
  __init__(self, hiddenlayer_units, learning_rate, dimension, epochs) : Constructor method to initialize the AutoEncoder with specified parameters.
  
  train_autoencoder(self, train) : Train the AutoEncoder using the provided training data (train). Prints the training loss at each epoch.
  
  transform_data(self, data) : Transform input data using the trained AutoEncoder. 

