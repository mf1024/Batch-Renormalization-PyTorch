# Batch-Renormalization-PyTorch
Batch Renormalization module  for PyTorch

Batch Renormalization implementation based on paper https://arxiv.org/abs/1702.03275 . 
Currently there is only 2D implementation for conv nets.

Usage is the same as for PyTorch [BatchNorm2D](https://pytorch.org/docs/stable/nn.html#batchnorm2d) class:
You intialize an instance by providing number of features (number of channels in conv layer).
Input is expected to be in shape (N, C, H, W), where: (N - number of samples per batch, C - number of channels, H - height, W - width)
