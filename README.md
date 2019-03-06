# GNR 652: Deep Learning Frameworks

Welcome to this follow up page about the talk on Deep learning frameworks at GNR 652 course.

To begin, let us narrow down from a high level of computer usage. There are three broad aspects one has to think about namely.
- Scale
- Hardware
- Software

## Scale
One of the first things is the scale of the problem at hand. This basically boils down to the size of the network you plan to build and the size of the dataset it is going to crunch. If you are training a small few layer network and using an MINST sized dataset, you will be fine with using a local setup without a GPU.

## Hardware
There are two options available for the type of hardware you can use. One is to run your code on a local machine you have physical access to. The other is to launch your code on cloud platforms by big companies like Amazon, Google, Microsoft and others. Another even better option is to look out for compute available within the campus.

### Local
There are two options we have here, a computer with or without Graphics Processing Unit(GPU). And as you might have studied in the course and maybe also read on the internet, a GPU can speed up your code sometime by over an order of magnitude. But a GPU is needed only when your network is huge and eats up a lot of data to get trained. For the assigmnents and homeworks in this course, a computer without GPU should be good enough. Even the laptop you own will be sufficient enough too. Although if you wish to build something bigger for your course project, you should consider moving out of your laptop.

### Cloud
The other option is to go run your code on Google Collaboratory which offers a Jupyter notebook interface where your code can utilize GPU on Google's cloud platform. This is an amazing option to try out as you get to run your code on GPUs for free. There are some limitations this lucrative option though. The GPU usage can be done only for short periods of time so it is only good for small projects or for proptyping a large project. Another con of this options is that you have to stick with Tensorflow or Keras as your deep learning frameworks of choice.

### @IITB
Campus offers us a lot of place you can run your code at. There very likely will be a common computer lab available for students to use. I'm aware of two such facilities, Bits nd Bytes lab at the Computer Science Department and PC Lab in the Electrical Engineering department. The PCs there will moslty be general purpose computers without a GPU but just reach out to the SysAds of your department and there might be a High performance machine setup for use. Like there are Ravan and Rudra, two high end machines for EE students that I know of.

If you are using any of the compute infra at campus, reach out the the administrators of the facility to find out how to go about using their setup. You can ask them if you want something installed, we SysAd are a friendly bunch. :D

Note: Make sure you use there resources judiciously and write an efficient code and keep following up on the runs. These are shared resources and should be used with other users in mind.

## Software
Software is where you have the most choices! Operating system was an issue in the initial days but it is not so much now. The most popular of the deep leanring frameworks work everywhere, Linux, MacOS and Windows. And regarding the programming language of development, Python is where all the libraries reside. Picking up Python is quite easy and with the current trend, is a must to be able to use one of the popular frameworks.

Listed below are few of the most popular deep learning frameworks out there. The choice here is again of how much control you want over your code and how much of your decisions you want to outsource to the framework. It is a huge task to compile an exhausting list of all te available frameworks so I'll just list down the one's that are widely used that I've worked with and inorder of difficulty as per me.

- Keras
- PyTorch
- TensorFlow
- Caffe