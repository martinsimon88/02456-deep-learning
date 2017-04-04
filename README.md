DTU course 02456 Deep learning
=======
This repository contains the exercises and supplementary material for course [02456 deep learning](http://www.kurser.dtu.dk/02456).

## Assignment1: Feedforward neural networks
The purpose of this assignment is to demonstrate that the MLPs can classify non-linear problems whereas simple logistic regression cannot and get acquainted with a simple Feedforward neural network.


## Assignment2: Convolutional neural networks
The purpose of this assignment is to experiment with inserting 2D-convolutional layers in the fully connected neural networks introduced in Assignment1. We'll further experiment with stacking of convolutional layers, max pooling and strided convolutions which are all important techniques in current convolutional neural network architectures. Lastly we'll try to visualize the learned convolutional filters and try to understand what kind of features they learn to recognize.

## Assignment3: Recurrent neural networks
The purpose of this assignment is to 

## Assignment4: Kaggle challenge
The purpose of this assignment is to familiarise with Kaggle.com and solve a data science challenge: Leaf Classification. 

The dataset consists approximately 1,584 images of leaf specimens (16 samples each of 99 species) which have been converted to binary black leaves against white backgrounds. Three sets of features are also provided per image: a shape contiguous descriptor, an interior texture histogram, and a ﬁne-scale margin histogram. For each feature, a 64-attribute vector is given per leaf sample.

The first task in a kaggle competition is to download, understand and preprocess the data. This we will do in the first section.

Afterwards, we will look into the type of neural network best suited for handling this type of data. For images, usually the convolutional neural network does a pretty good job, for timeseries (like the shape) usually the RNN is the network of choice.

Lastly, we will train the model and put the outputs in a submission file that we can submit to kaggle.


## Assignment5: Recurrent neural networks
The purpose of this assignment is to implement a simple Auto-Encoder (AE), a Variational Auto-Encoder (VAE) and a Variational Auto-Encoder with Semi-Supervised Learning (VAESSL)


## Assignment6: Recurrent neural networks
The purpose of this assignment is to train a neural network agent to navigate various environments from the OpenAI Gym.

Installation
------------
Please make sure that you read this section thoroughly and follow the installation guide from scratch before getting started with the exercises.

All exercises are written in Python programming language and formatted into Jupyter Notebooks. In order to run the exercises you must follow the below requirements:

**1. Install Anaconda (Python distribution)**

- Install Anaconda for Python 2.7 from https://www.continuum.io/downloads.

- The installer will ask you whether you want to add Python as a default and to your environment path. You should tick both of these options.

- Restart your terminal/command prompt for the environment variables to update.

**2. Install and upgrade theano**

- In a terminal/command prompt run: pip install theano

- In a terminal/command prompt run: pip install --upgrade https://github.com/Theano/Theano/archive/master.zip --no-deps

- If you run into problems installing Theano, please refer to: http://deeplearning.net/software/theano/index.html.

**3. Install and upgrade lasagne**

- In a terminal/command prompt run: pip install lasagne

- In a terminal/command prompt run: pip install --upgrade https://github.com/Lasagne/Lasagne/archive/master.zip --no-deps

Run the notebooks
------------
Download the repository from Github and run in a terminal/command prompt: jupyter notebook. This should start your default browser and you should be up and running. If you have issues while running the notebooks, we recommend that you use the newest version of Chrome.
