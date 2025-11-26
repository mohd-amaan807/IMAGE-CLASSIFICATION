# Image Classification (CIFAR-10)

## Overview

This project trains a convolutional neural network on the CIFAR-10 dataset. The goal is to classify small color images across ten categories, ranging from vehicles to animals. The notebook included in the repository walks through loading the dataset, building the model, training it, and evaluating its performance.

## Features

* Uses TensorFlow and Keras to build a clean, compact CNN
* Loads CIFAR-10 directly through `tf.keras.datasets`
* Includes model training, validation, and performance tracking
* Provides an easy starting point for experiments or extensions

## Getting Started

### 1. Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\\Scripts\\activate     # Windows
```

### 2. Run the notebook

```bash
jupyter lab   # or jupyter notebook
```

Open `IMAGE_CLASSIFICATION.ipynb` and run all cells.

## Model Summary

* Convolutional layers extract low-level and mid-level features
* Max pooling reduces spatial size and helps with generalization
* Dense layers map learned features to one of the ten target classes

## How to extend

* Add data augmentation
* Increase model depth
* Try transfer learning with MobileNet or ResNet
* Add early stopping or checkpoints

