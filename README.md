# CNN Object Classification Using CIFAR-10

A deep learning project that classifies uploaded images into one of ten object categories using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

## Overview

This project trains a CNN model using the CIFAR-10 dataset and allows users to upload an image for classification.

The model predicts the most likely object category and displays the prediction confidence along with the top classification results.

## Features

- CIFAR-10 dataset integration
- Convolutional Neural Network (CNN)
- Image upload functionality in Google Colab
- Automatic image preprocessing
- Confidence score prediction
- Top-3 prediction results
- Real-time classification from uploaded photos

## Dataset

The project uses the CIFAR-10 dataset, which contains 60,000 color images (32×32 pixels) across 10 classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Google Colab

## CNN Architecture

```text
Input Image (32x32x3)
          │
          ▼
Conv2D (32 Filters)
          │
          ▼
MaxPooling2D
          │
          ▼
Conv2D (64 Filters)
          │
          ▼
MaxPooling2D
          │
          ▼
Conv2D (64 Filters)
          │
          ▼
Flatten
          │
          ▼
Dense (64)
          │
          ▼
Dense (10 Softmax)
          │
          ▼
Predicted Class
```

## Model Training

- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 15
- Output Classes: 10

## Installation

Install required libraries:

```bash
pip install tensorflow numpy matplotlib opencv-python
```

## Usage

1. Open the notebook in Google Colab.
2. Run all cells.
3. Train the CNN model.
4. Upload an image.
5. View prediction results and confidence scores.

## Example Output

```text
Predicted Class:
CAT

Confidence:
96.52%

Top Predictions:
- Cat: 96.52%
- Dog: 2.11%
- Deer: 0.87%
```

## Learning Objectives

This project demonstrates:

- Deep Learning fundamentals
- Convolutional Neural Networks (CNN)
- Image classification
- Model training and evaluation
- Data preprocessing
- TensorFlow and Keras implementation

## Future Improvements

- Data augmentation
- Transfer Learning (MobileNet, ResNet)
- Web deployment using Flask
- Real-time webcam prediction
- Custom dataset support
- Model performance optimization

## Author
[hanira-bee](https://github.com/hanira-bee) and team
