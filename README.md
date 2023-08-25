# MNIST-Classification

This repository contains a project that demonstrates how to perform handwritten digit classification using the MNIST dataset and PyTorch. 

## About the Dataset
The **MNIST dataset** is a well-known benchmark dataset in the field of machine learning and computer vision, consisting of a collection of 28x28 grayscale images of handwritten digits (0-9) along with their corresponding labels.
It consists of the following:

-Training set: 60,000 images
-Test set: 10,000 images

Each image is a grayscale 28x28 pixel image, and the labels are integers indicating the digit in the image.

## Training & Evaluation

The model is trained using the training set of the MNIST dataset. 
During training, the model learns to minimize the cross-entropy loss by adjusting its weights through backpropagation with a learning rate 0f 0.001 for 10 epochs.
The trained model is evaluated on the test set to assess its performance. **Accuracy** and **Average** Loss are computed to provide a comprehensive evaluation of the model's classification performance.

## Results
After training and evaluation, the model's performance metrics are displayed. Additionally, an example test image along with the predicted label is visualized.