# ML classifier for classifying images based on their content. 
This repository contains a binary classifier which classifies images of memes and notes. The classifier was implemented on self made custom dataset.

This classifier is developed using 2 types of network, Dense Neural Network and Convolutional Neural Network. The Dense Neural Network is made from scratch using NumPy library.
While the Convolutional Neural Network is implemented using Pytorch deep learning Framework. 

## Dense Neural Network :
The images are first preprocessed and converted into grayscale images with dimensions 80x80.
 
 ```
 DenseNet(
    (dense1): Linear(in_features=6400, out_features=1000, bias=True)
    (dense2): Linear(in_features=1000, out_features=100, bias=True)
    (dense3): Linear(in_features=100, out_features=2, bias=True)
 )
 ```
 ### Result :
 Loss vs Epochs
 ![](https://github.com/M-NEXT/Memes-vs-Notes/blob/master/images/numpy1.png)
 
 Accuracy vs Epochs
 ![](https://github.com/M-NEXT/Memes-vs-Notes/tree/master/images/numpy2.png)
 
