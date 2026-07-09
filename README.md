# teachable-machine-cat-dog-classifier
A cat and dog image classification model trained using Google Teachable Machine and tested with Python using a Keras model.

This task is a simple image classification model that distinguishes between cats and dogs using a trained deep learning model.

## Overview

The model was trained using Google Teachable Machine with two image classes: Cat, Dog

After training, the model was exported in TensorFlow Keras format and tested using Python in Google Colab. The Python script loads the trained model, processes an input image, predicts its class, and displays the confidence score.

# Tools Used

- Google Teachable Machine
- Python
- TensorFlow
- Keras
- Google Colab

# Files

- predict.py: Python script used to load the trained model and classify an input image.
- catdog.ipynb: Google Colab notebook containing the model testing code.
- keras_model.h5: Trained Keras image classification model.
- labels.txt: File containing the class labels.
- test-image.jpg: Test image used for prediction.
- output1.png: Screenshot of the trained model test in Teachable Machine.
- output2.png: Screenshot of the Python prediction output.

# How It Works

1. Train the image classification model using Google Teachable Machine.
2. Export the trained model in TensorFlow Keras format.
3. Load the model using Python.
4. Read and preprocess the input image.
5. Resize the image to `224 x 224` pixels.
6. Normalize the image data.
7. Predict whether the image belongs to the Cat or Dog class.
8. Display the predicted class and confidence score.

# Prediction Result

The model predicted the test image as:

Class: cat
Confidence Score: 0.99905545
