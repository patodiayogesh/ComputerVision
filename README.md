# ComputerVision

This repository contains the assignments of course COMS 4732.

## Assignment 1
Problem 1: Image Denoising
    Implement a mean filter using "for" loop.
    Implement a mean filter using a filter matrix.
    Implement a Gaussian filter.

Problem 2: Edge Detection
    Implement a Delta (Gradient) filter.
    Implement a Laplacian filter.

Problem 3: Create Hybrid Images
    Implement Fourier transform
    Implement low and high pass filter and apply them to images
    Create a hybrid image using high-pass and low-pass fitlered images

## Assignment 2
The assignment deals with implementation of back-propagation.
We also look at various Gradient methods and observe how they work:
    Full Gradient Descent
    Stochastic Gradient Descent
    Stochastic Gradient Descent + Momentum
    AdaGrad
    Adaptive Moment Estimation (ADAM)

## Assignment 3
In this assignment we’ll build a simple convolutional neural network
in PyTorch and Train it to recognize natural objects using the CIFAR-10 dataset.
We observe the difference between training from scratch and fine-tuning a
pre-trained model

We also perform experiment to understand how a deep NN works.
The deep learning is quite powerful and can achieve great performance after training for a few epochs.
However, we still don't know why it works.
Thus, we first study activation map to analysis the region that triggers the final classification.
Then, we visualize a few kernels to infer what is learned in the neural network.
The results and inference can be viewd in the notebook.

## Assignment 4
Implement a Generative Adversarial Network to generate MNIST dataset