
# [EECS 498-007 / 598-005:](https://web.eecs.umich.edu/~justincj/teaching/eecs498/FA2019/) Deep Learning for Computer Vision

## Course Description

This course is a deep dive into details of neural-network based deep learning methods for computer vision. During this course, students will learn to implement, train and debug their own neural networks and gain a detailed understanding of cutting-edge research in computer vision. We will cover learning algorithms, neural network architectures, and practical engineering tricks for training and fine-tuning networks for visual recognition tasks. (quote from the course website)

The instructor is [Justin Johnson](https://cs.stanford.edu/people/jcjohns/). He received his PhD from Stanford, advised by [Fei-Fei Li](https://profiles.stanford.edu/fei-fei-li).

## Course Resources

The course resources can be found on the course website including

- lecture videos (fa2019 only, on Youtube)
- lecture notes (from C[S231@Stanford](https://cs231n.github.io) and related blogs)
- 6 assignments (can be downloaded freely and can be done on your own PC through Google Colab)

No autograder is provided though, but the correctness of completed assignment can be observed directly (like neural nets' accuracy etc.), charm of computer science...

## Assignment 1

A1 is divided into 2 parts.

### Pytorch 101

The first task consists in getting familiar with Pytorch operations, mostly in the manipulations on torch tensors. Very fundamental to future assignments, never miss it!

### k-Nearest Neighbor classifier

In this task you will implement a very naive classifier to be used on CIFAR-10 dataset. It's our very first step into computer vision!

My implementations can be found here:
[pytorch101.py](./A1/pytorch101.py), [knn.py](./A1/knn.py)

## Assignment 2

### Linear Classifiers

In this taks you will implement a linear classifier to be used on CIFAR-10 dataset. You will encounter 2 different types: SVM and Softmax, computing the loss, gradients both using naive loops and taking advantage of accelerated tensor operations. And of course you can *train* your classifiers!

### Two-layer Neural Network

In this task you will get a taste of so-called *neural networks* by implementing it! You will get a feeling of how those fancy neurons in neural net diagram represented by numbers operations during your implementation! You can also tune hyperparameters like learning rate or layer size to find your best model. This is a step further from linear classifier.

My implementations can be found here:
[linear_classifier.py](./A2/linear_classifier.py), [two_layer_net](./A2/two_layer_net.py)