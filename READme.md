# Cat vs Dog Classification using CNN 🐱🐶

A Deep Learning project that classifies images of cats and dogs using a Convolutional Neural Network (CNN) built with PyTorch.

## 📌 Project Overview

This project uses a custom CNN model to classify images into two categories:

- Cat
- Dog

## 🚀 Features

- Custom CNN Architecture
- Batch Normalization
- Max Pooling Layers
- Adam Optimizer
- Cross Entropy Loss
- Image Classification

## 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- Matplotlib

## Dataset Structure

dataset/
├── train/
│ ├── cats/
│ └── dogs/
└── test/
├── cats/
└── dogs/

## Model Architecture

- Conv2D → ReLU → BatchNorm → MaxPool
- Conv2D → ReLU → BatchNorm → MaxPool
- Conv2D → ReLU → BatchNorm → MaxPool
- Fully Connected Layer
- Output Layer (2 Classes)

## Training Configuration

- Batch Size: 32
- Optimizer: Adam
- Loss Function: CrossEntropyLoss
- Epochs: 10

## Installation

```bash
pip install -r requirements.txt
```

## Run

```bash
jupyter notebook
```

Open:

```text
catvsdogcnn.ipynb
```

## Future Improvements

- Data Augmentation
- Transfer Learning
- Hyperparameter Tuning
- Early Stopping

## Author

Zabi Shaik
