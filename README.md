# [WIP] Training an OCR model
## Dataset
[EMNIST from PyTorch](https://pytorch.org/vision/stable/generated/torchvision.datasets.EMNIST.html#torchvision.datasets.EMNIST) and [paper](https://www.westernsydney.edu.au/icns/resources/reproducible_research3/publication_support_materials2/emnist).

# Things that tripped me up
I'm trying to do/learn from scratch. Here's some things that I had trouble with initially.

## Labels and classes
For this dataset, the labels are just ints, which is fine for training, but bad for just visualizing the data. You have to convert them into a human readable format. I had to read the source library code to find what I needed to call the get the human readable names.  

## Rotated image
todo

## Model dimensions
todo


# Refs
1. [EMNIST from PyTorch](https://pytorch.org/vision/stable/generated/torchvision.datasets.EMNIST.html#torchvision.datasets.EMNIST) and [paper](https://www.westernsydney.edu.au/icns/resources/reproducible_research3/publication_support_materials2/emnist).
1. [PyTorch quickstart](https://pytorch.org/tutorials/beginner/basics/quickstart_tutorial.html)
    1. [PT without NN](https://pytorch.org/tutorials/beginner/nn_tutorial.html)