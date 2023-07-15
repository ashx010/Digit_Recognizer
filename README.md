# Digit Recognizer with Deep Learning Model (CNN)

This repository contains code for the "Digit Recognizer" competition on Kaggle. The goal of this competition is to accurately classify handwritten digits (0-9) from the famous MNIST dataset using a Deep Learning Model, specifically a Convolutional Neural Network (CNN).

## Competition Description

The "Digit Recognizer" competition is a classic machine learning problem where participants are challenged to build a model that can identify handwritten digits from the MNIST dataset. The dataset consists of 60,000 training images and 10,000 test images, each representing a single digit (0-9). The task is to correctly classify the test images with the highest accuracy possible.

## Project Structure

The repository has the following structure:

- `data/`: This directory should contain the MNIST dataset. You can download the dataset from the competition page on Kaggle and place the files here.
- Jupyter notebook contain the python code in the form of notebook (.ipynb) file
- The Project reads the data using Pandas.
- Maplotib.pyplot library is used to display the images.
- CNN : Convolutional Neural Network is used to train on image data.
- In CNN model, we make use of Convolutional, Pooling, Flatten, Hidden and Output layer to train model.
- We use Stochastic Gradient Descent as Optimizer and Categorial Cross Entropy for Loss funtion while training. 
- Achieve Accuracy score of ~0.987 after submission on kaggle.

## Dependencies

The following dependencies are required to run the code:

- Python3
- NumPy
- Pandas
- Matplotlib
- TensorFlow
- Keras
