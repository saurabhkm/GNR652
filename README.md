# GNR 652: Machine Learning and Deep Learning Frameworks

Welcome to this follow-up page about the session on Machine learning and Deep learning frameworks at GNR 652 course.

To begin, let us narrow down from a high level of computer usage. There are three broad aspects one has to think about.

- [Scale](https://github.com/saurabhkm/GNR652#scale)
- [Hardware](https://github.com/saurabhkm/GNR652#hardware)
- [Software](https://github.com/saurabhkm/GNR652#software)

## Scale
One of the first things is the scale of the problem at hand. This boils down to the size of the network you plan to build and the size of the dataset it is going to crunch. If you are training a small few layer network and using an MNIST sized dataset, you will be fine with using a local setup without a GPU.

## Hardware
There are two options available for the type of hardware you can use. One is to run your code on a local machine you have physical access to. The other is to launch your code on cloud platforms by big companies like Amazon, Google, Microsoft, and others. An even better option is to look out for available compute within the campus.

### Local
There are two options we have here, a computer with or without a Graphics Processing Unit(GPU). Moreover, as you might have studied in the course and maybe also read on the internet, a GPU can speed up your code sometime by over an order of magnitude. However, a GPU is needed only when your network is huge and eats up a lot of data to get trained. For the assignments and homework in this course, a computer without a GPU should be good enough. Even the laptop you own is sufficient too. Although if you wish to build something bigger for your course project, you should consider moving out of your laptop.

### Cloud
The other option is to run your code on Google Collaboratory which offers a Jupyter notebook style interface where your code can utilize GPU on Google's cloud platform. This is an amazing option to try out as you get to run your code on GPUs for free. There are some limitations this lucrative option though. The GPU usage can be done only for short durations, so it is only good for small projects or for prototyping a large project. Another con of this options is that you have to stick with Tensorflow or Keras as your deep learning frameworks of choice. I hear that PyTorch is now also available on Colab though, need to check it out!

### @IITB
The campus offers us many options you can run your code. There will very likely be a common computer lab available for students to use at each department. I'm aware of two such facilities, Bits and Bytes lab at the Computer Science Department and PC Lab in the Electrical Engineering department. The PCs there will mostly are general purpose computers without a GPU and should be sufficient for this course. However, just reach out to the SysAds of these departments, and there might be a High-performance machine setup for use. Like there are Ravan and Rudra, two high-end machines for EE students that I know of.

If you are using any of the compute infra at the campus, reach out to the administrators of the facility to find out how to go about using their setup. You can ask them if you want something installed, we SysAd are a friendly bunch. :D

Note: Make sure you use these resources judiciously and write efficient code and keep following up while your code runs. These are shared resources and should be used with other users in mind.

## Software
The software is where you have the most choices! The operating system was an issue in the initial days but is not so much now. The most popular of the deep learning frameworks work everywhere, Linux, MacOS, and Windows. Moreover, regarding the programming language of development, Python is where all the libraries reside. Picking up Python is quite easy and with the current trend, is a must to be able to use one of the popular frameworks.

Listed below are few of the most popular deep learning frameworks out there. The choice here is again of how much control you want over your code and how much of your decisions you want to outsource to the framework. It is a colossal task to compile an exhausting list of all the available frameworks, so I'll list down the ones that are widely used, and I've worked with and in order of the steepness of the learning curve for me. Most of the writeup is as per my understanding, and the content here is just the tip of the iceberg, but there are references at the end of each section you can go up to for diving in deeper.

- [Scikit-learn](https://github.com/saurabhkm/GNR652/tree/master/Scikit-learn)
- [Keras](https://github.com/saurabhkm/GNR652/tree/master/Keras)
- [PyTorch](https://github.com/saurabhkm/GNR652/tree/master/PyTorch)
- [Caffe](https://github.com/saurabhkm/GNR652/tree/master/Caffe)
- [TensorFlow](https://github.com/saurabhkm/GNR652/tree/master/TensorFlow)

**Note**: All these frameworks are rapidly developed and fast evolving. Please refer to their respective documentation in case you see this at a later date.