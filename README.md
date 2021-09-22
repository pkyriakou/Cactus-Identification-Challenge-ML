# Cactus-Identification-Challenge-ML
This repository contains the notebook submitted for the [Aerial Cactus Identification](https://www.kaggle.com/c/aerial-cactus-identification/overview) Kaggle Challenge. 

The challenge was a computer vision problem and it involved binary classification of whether cacti were present in a given photo or not. 

The task was solved by a deep convolutional neural network which was implemented using Tensorflow. 
Data augmentation was also used (horizontal flips and rotations) to increase the training data size.

The final accuracy on the held out test set was 99.8% with the data augmentation and 96.9% without. 
