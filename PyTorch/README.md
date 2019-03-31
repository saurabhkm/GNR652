# PyTorch

PyTorch is the most pythonic of all the DL frameworks discussed here. So If you're are a Python user you'll find it most intuitive and simple to develop with. PyTorch is also termed by many as one of the most modular frameworks out there. So let us begin with some fundamentals of how to get started with PyTorch before we write our very own deep network in it.

## Fundae
### Dataset
Dataset class provides an abstraction for the data used for training or testing. A dataset has three main functions that need to be defined:
- init: Initialization
- len: Total length of the dataset
- getitem: getter function for an item in the dataset

### Dataloader
The data-loader takes in a dataset object and provides the functionality of preprocessing in the form of transformations and preparing mini-batches.

### Model
A model in PyTorch is defined with parent class as the nn.Module. It needs to have two methods defined:
- init: Initialize the network
- forward: Define the dataflow through the network

In essence, we initialize the layer that makes up our network here with appropriate parameters. The forward method is where we define how the given input is to be handled by the initialized network and specifically how it passes through the layers in the init method. There are various layers that are available for use to build our model or define custom ones.

### Training
For training, we define a loss function that we want to use along with an optimizer to help us do the backpropagation step. There are various optimizers built in that we can use out of the box.

## ConvNet MNIST Classifier
A simple example of a convolutional network for MNIST classification can be found here: https://github.com/pytorch/examples/tree/master/mnist


## References:
PyTorch official tutorials: https://pytorch.org/tutorials/

PyTorch Documentation: https://pytorch.org/docs/stable/