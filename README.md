# CIFAR-10_Classification
A PyTorch implementation of a custom neural network architecture for CIFAR-10 image classification, featuring attention mechanisms and data augmentation.

## Key Features

- Custom neural network architecture with attention mechanisms
- Data augmentation pipeline including:
  - Random cropping
  - Horizontal flipping
  - Rotation
  - Color jitter
  - Random erasing
- Training with:
  - AdamW optimizer
  - OneCycleLR learning rate scheduler
  - Mixed-precision training
  - Label smoothing
- Achieves ~92.7% validation accuracy on CIFAR-10

## Model Architecture

The model consists of:
- Stem convolutional layer
- Multiple attention-based blocks with residual connections
- Intermediate downsampling
- Classifier head

## Requirements

- Python 3.x
- PyTorch
- torchvision
- matplotlib

## Results

The model achieves:
- Training accuracy: ~90.9%
- Validation accuracy: ~92.7%

Training curves for loss and accuracy are included in the notebook.