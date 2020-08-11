# Handwritten-Digit-Recognition

## What is Handwritten Digit Recognition?
The handwritten digit recognition is the ability of computers to recognize human handwritten digits. It is a hard task for the machine because handwritten digits are not perfect and can be made with many different flavors. The handwritten digit recognition is the solution to this problem which uses the image of a digit and recognizes the digit present in the image.

## Problem Statement
The challenge in handwritten digit recognition is mainly caused by the writing style variations of every single individual. So, it is not easy for the machine to recognize the handwritten digits accurately like the humans do. Hence, robust feature extraction is very important to improve the performance of machines.

## Deep learning
Deep learning is a class of machine learning that uses multiple layers to progressively extract higher level features from the input. Therefore, deep learning reduces the task of developing new feature extractor for every problem. This characteristic of Deep Learning is a major step ahead of traditional Machine Learning.
> In this particular project we will use Convolutional Neural Networks (CNN)

## Steps to implement the CNN handwritten digit recognition GUI App:
1. Import the libraries and load the MNIST dataset
2. Data Preprocess and Normalize
3. Create the model
4. Train the model
5. Evaluate the model
6. Create GUI to predict digits

## GUI to predict Digits
I tried building the GUI App using Tkinter package as it is the fastest and easiest way to create the GUI applications. It provides a variety of common GUI elements – such as buttons, menus and various kinds of entry fields and display areas but i kept on getting **only supported in windows and Mac Os** so i therefore opted for a **Web based GUI**. It works well as you can  draw arbitrary digits into a browser, and see real-time predictions.

