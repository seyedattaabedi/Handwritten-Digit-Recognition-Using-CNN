# Handwritten Digit Recognition Using CNN

This project implements a Convolutional Neural Network (CNN) using TensorFlow/Keras to recognize handwritten digits from images based on the MNIST dataset.

## Dataset

The MNIST dataset contains 70,000 grayscale images (28×28 pixels) of handwritten digits from 0 to 9.

## Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib

## Model Architecture

* Conv2D (8 filters, ReLU)
* MaxPooling2D
* Flatten
* Dense (32 neurons, ReLU)
* Output Layer (10 classes)

## Workflow

1. Load and preprocess the MNIST dataset
2. Normalize image values
3. Build and train the CNN model
4. Evaluate model performance
5. Save the trained model
6. Predict handwritten digits from custom images using OpenCV

## Results

* Training Accuracy: ~99.4%
* Validation Accuracy: ~98.4%

## Goal

The objective of this project is to build an accurate handwritten digit recognition system while gaining practical experience in convolutional neural networks, image preprocessing, and computer vision applications.
