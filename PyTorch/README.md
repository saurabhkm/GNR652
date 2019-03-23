# PyTorch

PyTorch is the most pythonic of all the DL frameworks discussed here. So If you're are a Python user you'll find it most intuitive and simple to develop with. PyTorch is also termed by a lot of people as one of the most modular frameworks out there. So let us begin with some fundamentals of how to get started with PyTorch before we write our very own deep network network in it.

## Fundae
### Dataset
Dataset class provides abstraction for the data used for training or testing. A dataset has three main functions that need to be defined:
- init: Initialization
- len: Total lenght of the dataset
- getitem: getter function for a item in the dataset

### Dataloader
The datalaoder takes in a dataset object and provides functionality of preprocessing in the form of transofmations and preparing minibatches.

### Model
A model in PyTorch is defined with parent class as the nn.Module. It needs to have two methods defined:
- init
- forward
In essence we initialize the layer that will make up our network here with appropriate parameters. The forward methods is where we define how the given input is to be handelled by the initialized network and specifically how it passes through the layers in the init method. There are various layers that are available for use to build our model or define custom ones.

### Training
For training we define a loss function that we want to use along with an optimizer to help us do the backpropagation step. There are various optimizers built in that we can use out of the box.

## ConvNet MNIST Classifier
A simple example of a convolutional network for MNIST classification can be found at here: https://github.com/pytorch/examples/tree/master/mnist


## References:
PyTorch official tutorials: https://pytorch.org/tutorials/

PyTorch Documentation: https://pytorch.org/docs/stable/