# Neural Network Machine Learning Model
## Project Overview
This project builds a simple neural network using TensorFlow and Keras to classify clothing images from the Fashion MNIST dataset.

## Problem Statement
Image classification is an important task in machine learning. The goal of this project is to train a neural network model that can correctly identify different categories of clothing images.

## Dataset Information
The Fashion MNIST dataset contains grayscale images of clothing items such as shirts, shoes, bags, and dresses.

## Tools and Technologies Used
- Python
- TensorFlow
- Keras
- Jupyter Notebook
- NumPy

## Data Preparation
The dataset was loaded from TensorFlow Keras datasets and normalized by dividing pixel values by 255.

## Model Architecture
- Flatten Layer
- Dense Layer (128 neurons, ReLU)
- Output Layer (10 neurons)

## Model Training
The model was trained for 5 epochs using the Adam optimizer and Sparse Categorical Crossentropy loss function.

## Results
The model achieved approximately 82% test accuracy on the Fashion MNIST dataset.

## Conclusion
This project demonstrates the basic workflow of building, training, and evaluating a neural network model for image classification.
