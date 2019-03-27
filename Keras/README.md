# Keras

Keras offers a high level deep learning API to build deep neural networks. It is the easiest to use out of all the DL frameworks we shall discuss here and has simply runs out of the box. There are many ready to use tools for data loading, and preprocessing. Keras is high level wrapper with its backend being two other popular DL frameworks, Tensorflow and Theano, but does not involve any of the complications of these frameworks.


## Fundae
Keras has a quite scikit-learn style interface for training and evaluating models. A model class is the main abstraction available in Keras and we can stack layes and build an architecture that we want. We can specify the activations right in the layers config and once all feels good go ahead and compile the model. The compile method is to be called on the model object and here is where we specify our loss function, optimizer and performance metrics. There are various inbuilt layes, loss functions, optimizers and and performance metrics in Keras that can be used out of the box.

Once we are done setting up the model architecture along with loss, optmizer and metrics we can now use the fit method to feed data to the model and train it. The inferface for the fit method is very similar to how the fit method in sklearn is used. The fit method takes features and labels array along with number of epochs to train for, bathc size as paraemters along with other customizations if needed.

Once we have trained model we can test it by calling an evaluate method on the model. The evaluate method is also similar to how one would test in sklearn, it takes the test features and labels arrays with batch size and calculates the performance metrics. 

Now seeing such a simpe development cycle one might be inclined to believe Keras is just for beginers and not that powerful. But don't get fooled by the simple workflow. Keras is a framework that packs a lot of power while still offering a much simpler development workflow. You can build almost any deep learning architecture out there in Keras!


## ConvNet MNIST Classifier
A example of Alexnet implemented in Keras for MNIST classification:
https://github.com/keras-team/keras/blob/master/examples/mnist_cnn.py

**See how short the code is!**


## References
Project homepage: https://keras.io