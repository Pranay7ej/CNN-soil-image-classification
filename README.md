# CNN-soil-image-classification
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
Here, I tried to classify different types of soil based on image recognition via Convolutional Neural Networks (CNN). 
I'd used Adam Optimizer from Keras and ReLU activation function.

The accuracy I got was around 90%. It can be improved by using supporting data on soil pH, texture and drainage which will be used to ensemble the CNN with a Random Forest Regression algorithm.

The data used for this is comes from google images. There were then saved into seperate files based on their soil class into 4 types (Alluvial, Black, Clay, Red).   

The images are preprocessed using the Keras ImageDataGenerator class. This resizes to an approximate size for the algorithm (299,299,3) pixels.

The images were also normalised so that elements range from 0->1 instead of 0->255.
