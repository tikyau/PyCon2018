# PyCon2018
Source Code, Materials and Powerpoints for PyCon 2018 ML session

# Training, hyperparameter tune, and deploy with TensorFlow
Introduction
This tutorial shows how to train a simple deep neural network using the MNIST dataset and TensorFlow on Azure Machine Learning. MNIST is a popular dataset consisting of 70,000 grayscale images. Each image is a handwritten digit of 28x28 pixels, representing number from 0 to 9. The goal is to create a multi-class classifier to identify the digit each image represents, and deploy it as a web service in Azure.

For more information about the MNIST dataset, please visit Yan LeCun's website.

# Train a classification model with automated machine learning
In this tutorial, you'll learn how to generate a machine learning model using automated machine learning (automated ML). Azure Machine Learning can perform algorithm selection and hyperparameter selection in an automated way for you. The final model can then be deployed following the workflow in the Deploy a model tutorial.

Similar to the train models tutorial, this tutorial classifies handwritten images of digits (0-9) from the MNIST dataset. But this time you don't to specify an algorithm or tune hyperparameters. The automated ML technique iterates over many combinations of algorithms and hyperparameters until it finds the best model based on your criterion.
