Welcome to this follow up page about the talk on Deep leanring frameworks at GNR 652 course.

To begin, let us narrow down from higher level of computer usage.

# Scale
One of the first thing to think about is the scale of your problem. This basically boils down to the size of the network you plan to build and the size of the dataset it is going to crunch. If you are training a few layer network and using an MINST sized dataset, you will be fine with using a local setup without a GPU.

# Hardware
There are two options available for the type of hardware you can to use. First is to run your code on a local machine you have physical access to. The other is to launch your code on cloud platforms by big companies like Amazon, Google, Microsoft and others.

## Local
There are two options we have here, a computer with or without Graphics Processing Unit(GPU). And as oyu have studied in the course and maybe also read on the internet, a GPU can speed up your code sometime by an order of magnitude. But that is when you want to your network is huge and eats up a lot of data to get trained. For this course, a computer without GPU is good enough.

## Cloud
Another option is to go run your code on Google Collaboratory which offers a Jpyter notebook interface where your code can utilize GPU on Google's cloud platform. There are limitations this lucrative option though. The code 

# Software