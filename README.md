# Saliency Detection

Saliency describe the spatial locations in an image that attract human eye gaze. There
are various approaches to generate saliency map, here we try to explore the use of one
such method which uses convolutional neural networks, MLNet

The model combines features extracted at different levels of the CNN and the network
tries to minimize the loss function through stochastic gradient descent. The model is
trained and tested on the SALICON dataset. This approach differs from other CNN
based approaches in that it does not employ fully convolutional networks and extracts
feature maps from different levels of the network.

## Paper implemented 
Marcella Cornia, Lorenzo Baraldi, Giuseppe Serra, and Rita Cucchiara. A Deep Multi-
Level Network for Saliency Prediction. In International Conference on Pattern Recog-
nition (ICPR), 2016.
link - https://arxiv.org/pdf/1609.01064.pdf
