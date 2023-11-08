# FINE_TUNING_GESTURE
Here is a part of the code I had to write during my internship at ISIR. This code extract labels associated with movement features from a gesture dataset, and teach a deep-learning model to recognize these gesture on untrained data.

To summarize, the code is made of 4 different parts :
  1 - Extracting the labels/features from .elan files (using the documentation of the dataset)
  2 - Doing statistics over the labels/features
  3 - Preprocessing the labels/features to prepare the data for machine-learning training (using Keras/TensorFlow)
  4 - Training the model (LSTM, Keras, TensorFlow)
