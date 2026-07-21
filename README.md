# CNN Image Classification using PyTorch

## Overview

This project implements a Convolutional Neural Network (CNN) using PyTorch to classify images from the CIFAR-10 dataset.

## Dataset

CIFAR-10 contains 50,000 color images of size 32×32 in 10 classes.

## Model Architecture

- Conv2D (3 → 32)
- ReLU
- MaxPool2D
- Conv2D (32 → 64)
- ReLU
- MaxPool2D
- Conv2D (64 → 128)
- ReLU
- MaxPool2D
- Fully Connected Layer
- Output Layer (10 Classes)

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib

## Results

- **Test Accuracy:** **74.8%**
- Dataset: CIFAR-10
- Saved Model: `best_model.pt`

## Files

- CNN_CIFAR10_Image_Classification.ipynb
- best_model.pt
- requirements.txt
