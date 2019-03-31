# Caffe

CAFFE(Convolutional Architecture for Fast Feature Embedding) is one of the older frameworks and also one of the fastest out there(at least when I used it in early 2016). The Berkeley Vision Group develops it, and the first release came out in late 2013. Caffe has a very different development style than the other frameworks we shall see here.


## Fundae
We need to write two prototxt files namely the networkArchitecture.prototxt and the solver.prototxt. The input data can be in the form of raw images and also can be from a database. We can do bulk image transformations and other preprocessing on the datasets. An exciting feature of Caffe is that we can visualize our network architecture with just a single command. Most of the standard neural network layers are available out of the box and can be used in the networkArchitecture.prototxt file to construct the required architecture.

### Network architecture file
- The location of input data
- A mean image file for normalization
- The individual layers and construct the network
- Any image transformation if necessary

### Solver file
- Location of the above network architecture file on disk
- Learning parameters like learning rate, momentum, etc.
- Preferences
- Number of epochs
- Saving intermediate models
- CPU/GPU flag


## ConvNet MNIST Classifier
A detailed example of this is available on the official homepage:http://caffe.berkeleyvision.org/gathered/examples/mnist.html


## References
Project homepage: http://caffe.berkeleyvision.org