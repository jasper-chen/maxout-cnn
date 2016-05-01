# Theano implentation of Maxout
## Summary
This repository contains code written in Theano that uses the maxout architecture researched by Goodfellow et al in [this paper] (http://arxiv.org/pdf/1302.4389.pdf). The objective of the network is to classify images on CIFAR-10. The architecture consists of two convolutional layers, two pooling operations, a maxout layer and a softmax operation. The maxout layer is modular and can have any number of affine units.

## Results
~70% accuracy with 5 affine units. 


