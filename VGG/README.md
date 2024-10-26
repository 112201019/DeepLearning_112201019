# VGG-16 Model Implementation in PyTorch

This repository contains a custom implementation of the VGG-16 convolutional neural network (CNN) architecture in PyTorch. This model is specifically designed for **Project FacePass**, a facelock system focusing on face recognition. The code enables the loading of pretrained weights from the Hugging Face model hub to initialize all kernel values, allowing the model to work effectively with facial images.

## Features

- **VGG-16 Architecture**: Constructed from scratch to offer an in-depth understanding of CNN layers and their parameters.
- **Pretrained Weights**: Loads kernel values from a pretrained VGG-16 model on facial datasets via Hugging Face.
- **Layer-by-Layer Parameter Initialization**: Every layer's input parameters are specified, facilitating customizability and clarity in understanding model construction.

## Project Overview

This implementation is a part of **Project FacePass**, which is focused on building a secure facelock system. The VGG-16 model, known for its deep architecture and accuracy in image recognition, is tailored here to recognize faces accurately.

## File Overview

- **vgg16.ipynb**: Jupyter notebook containing the code for implementing the VGG-16 model from scratch. It includes explanations, code cells, and references to the pretrained weights for each layer.

## Requirements

- Python 3.7+
- PyTorch
- torchvision
- numpy
- Hugging Face transformers (for pretrained weights)

Install dependencies using:
```bash
pip install torch torchvision transformers numpy

