# Overview
This script performs sentiment analysis on movie reviews from the IMDB dataset using a neural network built with TensorFlow and Keras.<br> The task is to predict whether a movie review is positive or negative based on the text data.<br> The neural network model is a simple fully connected (dense) model.

# Features
Data Loading: Loads the IMDB dataset using tensorflow.keras.datasets.imdb.<br>
Data Preprocessing: Converts the text data (movie reviews) into a format suitable for neural network training, including one-hot encoding the words.<br>
Model Building: Creates a basic neural network model using Keras, consisting of dense layers.<br>
Model Training: Trains the model using training data and evaluates it on validation and test sets.<br>
Visualization: Plots training and validation loss/accuracy over epochs using matplotlib.<br>

# Technologies Used
TensorFlow: Framework for building and training the neural network.
Keras: High-level neural network API used for building models.
NumPy: For handling arrays and vectorized operations.
Matplotlib: For plotting training and validation loss/accuracy graphs.


# Import necessary modules:

import numpy as np <br>
from tensorflow import keras<br>
from tensorflow.keras import layers<br>
from tensorflow.keras.datasets import imdb<br>
import matplotlib.pyplot as plt<br>

# Import Code
To Improt the code go to google colab and open a notebook from github using 
TE109/Movie-Review-Analysis as the path


# 
