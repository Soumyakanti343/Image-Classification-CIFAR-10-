# CIFAR-10 Image Classification Using CNN (PyTorch)

## Project Overview

This project implements Convolutional Neural Networks (CNNs)
using PyTorch to classify images from the CIFAR-10 dataset.

Two CNN architectures are implemented and compared based
on their classification performance.

## Dataset

CIFAR-10 consists of 60,000 RGB images divided into 10 classes.

- Training Images: 50,000
- Testing Images: 10,000
- Image Dimensions: 32 × 32
- Number of Classes: 10

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Pandas
- Scikit-learn
- Jupyter Notebook

## CNN Architectures

### 1. Original CNN
- 3 Convolutional Layers
- ReLU Activation
- Max Pooling
- Fully Connected Layers

### 2. Deeper CNN
- 4 Convolutional Layers
- Batch Normalization
- ReLU Activation
- Max Pooling
- Dropout
- Fully Connected Layers

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Training Loss

## Project Structure

CIFAR10-CNN-Image-Classification/
│
├── Image Classification (CIFAR 10).ipynb
├── requirements.txt
├── README.md
├── .gitignore
└── results/

## Installation

Install dependencies:

pip install -r requirements.txt

## Run the Project

Open Jupyter Notebook:

jupyter notebook

Run CNN_CIFAR10_Assignment.ipynb

The CIFAR-10 dataset will be downloaded automatically.

## Results

Results from both CNN architectures are evaluated
and compared in the notebook.

## Author

Soumya Kanti Upadhyay
