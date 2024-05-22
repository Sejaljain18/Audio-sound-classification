Welcome to the Sound/Audio Classification project! This repository contains code and resources for training a deep learning model to classify urban sounds using the UrbanSound8K dataset.

Introduction:-
This project focuses on classifying various urban sounds using a deep learning approach. By leveraging convolutional neural networks (CNNs), we aim to accurately categorize different types of sounds typically found in urban environments, such as car horns, sirens, and dog barks.

Dataset:-
The dataset used for this project is the UrbanSound8K dataset. It consists of 8,732 labeled sound excerpts (<=4s) of urban sounds from 10 classes:
Air Conditioner
Car Horn
Children Playing
Dog Bark
Drilling
Engine Idling
Gunshot
Jackhammer
Siren
Street Music
The audio files are pre-sorted into ten folds to support cross-validation. The dataset is publicly available and can be downloaded from the UrbanSound8K dataset webpage.


Model Architecture:-
The model is based on a convolutional neural network (CNN) architecture, which is well-suited for processing audio spectrograms. The primary components of the model include:
Convolutional layers for feature extraction
Pooling layers to reduce dimensionality
Fully connected layers for classification
The model is implemented using TensorFlow/Keras.

Results:-
Detailed results of the model's performance, including accuracy, precision, recall, and F1-score, are available in the results directory. Visualizations of training progress and confusion matrices are also provided.
