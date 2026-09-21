# Flower Image Classification using Single-Layer Perceptron

This project implements a **Deep Learning single-layer perceptron** to classify flower images into two different flower categories.

The images are loaded from folders, resized to `60 × 60`, normalized, converted into numerical data, and then used to train a perceptron model using **TensorFlow**.

## Objective

The main objective of this project is to understand how a **single-layer perceptron** can be used for image classification.

The model takes the pixel values of a flower image as input and predicts its flower category.

## Project Workflow

1. Load the flower image dataset
2. Read images using OpenCV
3. Resize images to `60 × 60`
4. Convert images into NumPy arrays
5. Normalize pixel values between `0` and `1`
6. Encode flower labels into numerical values
7. Convert labels into one-hot encoded values
8. Split the dataset into training and testing sets
9. Flatten the images into one-dimensional arrays
10. Build a single-layer perceptron using TensorFlow
11. Train the model using Gradient Descent
12. Calculate the classification loss during training

## Technologies Used

- Python
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn

## Image Preprocessing

Each image is resized to:

```text
60 × 60
