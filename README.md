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
 
 ![](https://github.com/M-NEXT/Memes-vs-Notes/blob/master/images/numpy2.png)
 
 
 ## Convolutional Neural Network :
The images are first preprocessed and converted into grayscale images with dimensions 80x80.
 
 ```
Network1(
  (conv1): Conv2d(3, 8, kernel_size=(7, 7), stride=(1, 1))
  (conv2): Conv2d(8, 16, kernel_size=(6, 6), stride=(1, 1))
  (fc1): Linear(in_features=57600, out_features=50, bias=True)
  (fc2): Linear(in_features=50, out_features=20, bias=True)
  (fc3): Linear(in_features=20, out_features=2, bias=True)
)
 ```
 ### Result :
 Loss vs Epochs
 
 ![](https://github.com/M-NEXT/Memes-vs-Notes/blob/master/images/pytorch1.png)
 
 Accuracy vs Epochs
 
 ![](https://github.com/M-NEXT/Memes-vs-Notes/blob/master/images/pytorch2.png)
 
