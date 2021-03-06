# TinyANNs
## Overview:
Deep neural networks (DNNs) have recently
achieved great success in many visual recognition tasks. However,
training large deep neural network models are computationally
expensive and memory intensive. Hence, the natural idea is
to perform compression and acceleration of the DNN without
significantly decreasing the performance of it. In this repository,
a new method of a training a neural network having a small
computation time and fewer parameters is discuss. Feature
extraction is done using Discrete Wavelet Transform (DWT)
method. A voting-based classifier consisting of a team of tiny
artificial neural networks is introduce. The voting-based classifier
combines all the classification votes from the different sub-bands
(models) to get the final voted class identity label, and thus,
achieving the similar classification accuracy of the standard
neural network architecture. This has been demonstrated on
benchmark data-sets of MNIST and EMNIST.
## Requirements:
Install TorchVision via :
```
pip install torchvision
```
## Datasets:
1) MNIST [Download Link](http://yann.lecun.com/exdb/mnist/)
2) EMNIST [Download Link](https://www.nist.gov/itl/products-and-services/emnist-dataset)


[D](https://github.com/ASP-AI/TinyANNs/blob/master/OrignalNetwork.ipynb)
