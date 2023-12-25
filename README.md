# Dogs-vs-Cats
A Convolutional Neural Network (CNN) Model to classify Dogs and Cats


![image](https://miro.medium.com/v2/resize:fit:1400/1*EvMbMNRHm_aOf1n4tDO1Xg.jpeg)

# Details
This project aims to develop a model that can classify images of Cats and Dogs. The project achieves it by building and training a CNN model using Keras. The model is trained using Kaggle Dataset *Dogs-vs-Cats* and uses Data Augmentation. The model provides an Accuracy of 84%.

# Dataset
The project uses Dogs-vs-Cats Dataset from Kaggle.(Ended 10 yrs ago - as of 17/12/23)\

The Dataset consists of 25,000 pictures of Dogs and Cats in its Training Data. The Test data contains 12,500 unlabelled pictures of Dogs and Cats. The motive of the competition is to develop a model that correctly predicts the Dogs and Cats, based on the given dataset.

[Competition Link](https://www.kaggle.com/competitions/dogs-vs-cats)

# Model
The model built is a Convolution Neural Network (CNN) model. A Convolutional Neural Network (CNN) is a type of Deep Learning neural network architecture commonly used for image-related tasks. These type of models are commonly used in Computer Vision. 

The model is built with Keras Library. Keras is an open-source library that provides a Python interface for artificial neural networks. Keras acts as an interface for the TensorFlow library. Keras follows best practices for reducing cognitive load: 
  *  It offers consistent & simple APIs
  *  It minimizes the number of user actions required for common use cases, and 
  *  It provides clear & actionable error messages.
The project utilizes Keras for Data Augmentation with the help of (ImageDataGenerator)[https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image/ImageDataGenerator] API, which generates batches of tensor image data with real-time data augmentation.

(Keras Documentation)[https://keras.io/]

# Model Architecture
![model](https://github.com/LogeswaranSR/Dogs-vs-Cats/assets/131794661/5bcded4b-e712-411a-aff0-c78a8cae32e0)

# Inference
![inference](https://github.com/LogeswaranSR/Dogs-vs-Cats/assets/131794661/75c76940-5656-4989-85d3-6216a8a72b45)
