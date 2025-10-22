# MNIST-CNN
My CNN implementation on the MNIST dataset

## About
This is an attempt by me to write a simple CNN in PyTorch for the MNIST handwritten numerical digits dataset.

It has:
- 3 convolution + activation and maxpool layers
- trained for 10 epochs
- 0.5 dropout

I haven't implemented early stopping because it's just 10 epochs and the dataset quality is alright. \
Test - Avg Loss: 0.0238, Accuracy: 99.40%

Other metrics can be found in the notebook (F1, recall, precision, etc)

## References
- [Gradient-based learning applied to document recognition](https://ieeexplore.ieee.org/abstract/document/726791)
- [CNN wikipedia](https://en.wikipedia.org/wiki/Convolutional_neural_network)
