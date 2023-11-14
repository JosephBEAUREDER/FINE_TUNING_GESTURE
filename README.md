# FINE_TUNING_GESTURE
Here is a part of the code I had to write during my internship at ISIR.

The goal of the internship was to create an annotated dataset of gesture, and use this dataset to train a deep-learning model, in order to generate more meaningful gestures on Embodied Conversational Agent (ECA).

This code extract labels associated with movement features from a gesture dataset, and teach a deep-learning model to recognize these gesture on untrained data.

To summarize, the code is made of 4 different parts :

* 1 - Extracting the labels of the movements from .elan files (using the documentation of the dataset)

* 2 - Extracting the movements data from the .H5 files (PATS dataset)
  
* 3 - Doing statistics over the labels/features
  
* 4 - Preprocessing the labels/features to prepare the data for machine-learning training (using Keras/TensorFlow)
  
* 5 - Training the model (LSTM, Keras, TensorFlow)
