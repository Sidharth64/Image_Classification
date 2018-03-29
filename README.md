# Image_Classification

This repository contains a basic implementation of image recognition using the dogs vs cats image classification dataset loaded from fast.ai. The dataset comprised of images of dogs and cats equally balanced.In order to build the model, a Convolutional Neuretwork (21 layers) with relu activation and dropout was trained from scratch.The output gives us the probability of a test sample for both the classes using the softmax activation.

Python Libraries used :

1)library(PIL.IMAGE) #to load a single image file .

2)library(numpy) #for preprocessing, data manipulation and converting image into array of pixel values.

3)library(glob) #for loading the complete set of images ina variable.

4)library(keras.models) #for bulding a Sequential model.

5)library(keras.layers) #for stacking different layers in the model.

6)library(keras.utils) #for converting terget variable to a categorical variable.

7)library(keras.optimizers) #for using ADAM optimizer.
