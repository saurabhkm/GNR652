# GNR 652: Deep Learning Frameworks

Welcome to this follow up page about the talk on Deep learning frameworks at GNR 652 course.

To begin, let us narrow down from a high level of computer usage. There are three broad aspects one has to think about namely.
- Scale
- Hardware
- Software

## Scale
One of the first things is the scale of your problem at hand. This basically boils down to the size of the network you plan to build and the size of the dataset it is going to crunch. If you are training a few layer network and using an MINST sized dataset, you will be fine with using a local setup without a GPU.

## Hardware
There are two options available for the type of hardware you can use. First is to run your code on a local machine you have physical access to. The other is to launch your code on cloud platforms by big companies like Amazon, Google, Microsoft and others.

### Local
There are two options we have here, a computer with or without Graphics Processing Unit(GPU). And as oyu have studied in the course and maybe also read on the internet, a GPU can speed up your code sometime by an order of magnitude. But that is when you want to your network is huge and eats up a lot of data to get trained. For this course, a computer without GPU is good enough.

### Cloud
Another option is to go run your code on Google Collaboratory which offers a Jupyter notebook interface where your code can utilize GPU on Google's cloud platform. There are limitations this lucrative option though. 

### @IITB
Campus offers us a lot of place you can run your code at. There very likely will be a common computer lab available for students to use. I'm aware of two such facilities, Bits nd Bytes lab at the Computer Science Department and PC Lab in the Electrical Engineering department. The PCs there will moslty be general purpose computers without a GPU but just reach out to the SysAds of your department and there might be a High performance machine setup for use. Like there are Ravan and Rudra, two high end machines for EE students that I know of.

If you are using any of the compute infra at campus, reach out the the administrators of the facility to find out how to go about using their setup. You can ask them if you want something installed, the SysAd are a friendly bunch. I'm one too :D

Note: Make sure you use there resources judiciously and write an efficient code and keep following up on the runs. These are shared resources and should be used with other users in mind.

## Software