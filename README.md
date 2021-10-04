# ML classifier for classifying images based on their content. 
This repository contains a binary classifier which classifies images of memes and notes. The classifier was implemented on self made custom dataset.

This classifier is developed using 2 types of network, Dense Neural Network and Convolutional Neural Network. The Dense Neural Network is made from scratch using NumPy library.
While the Convolutional Neural Network is implemented using Pytorch deep learning Framework. 

## Dense Neural Network :
The images are first preprocessed and converted into grayscale images with dimensions 80x80.
 
 ```DenseNet(
    (dense1): Linear(in_features=30000, out_features=10000, bias=True)
    (dense2): Linear(in_features=10000, out_features=5000, bias=True)
    (dense3): Linear(in_features=5000, out_features=1000, bias=True)
    (dense4): Linear(in_features=1000, out_features=500, bias=True)
    (dense5): Linear(in_features=500, out_features=100, bias=True)
    (dense6): Linear(in_features=100, out_features=50, bias=True)
    (dense7): Linear(in_features=50, out_features=2, bias=True)
 )```
