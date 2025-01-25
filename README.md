**Overview**

This project focuses on building and training Deep Neural Networks (DNNs) to recognize handwritten digits, a classic machine learning problem widely used to understand and evaluate the performance of classification models. The repository offers two implementations:

- Python-based DNN for a hands-on approach to neural network fundamentals.
- Keras-based DNN for a more streamlined and efficient model-building process.
- The project leverages the MNIST dataset for digit recognition and allows integration with custom handwritten samples for testing model adaptability. Additionally, the repository provides visualization tools to analyze the performance of trained models.

**This project is ideal for anyone looking to:**

- Learn about neural network fundamentals.
- Experiment with handwritten digit recognition.
- Compare low-level and high-level deep learning approaches.

**1. DNN in Python**

This script contains a custom implementation of a Deep Neural Network using Python libraries (e.g., NumPy) without the use of high-level frameworks. It demonstrates the fundamental steps of building a DNN for handwritten digit recognition, including:

- Data preprocessing.
- Model architecture (e.g., input, hidden, and output layers).
- Training and evaluation on the MNIST dataset or custom data.
  
**2. DNN in Keras**

This script is a Keras-based implementation for recognizing handwritten digits. It utilizes the MNIST dataset and follows a streamlined approach with the following features:

- Predefined layers for efficient model building.
- Faster training and higher accuracy.
- Options for tuning hyperparameters (e.g., epochs, learning rates, optimizers).

**3. Custom Digits Folder**

This folder contains custom handwritten digit samples that can be added to the dataset for model testing and evaluation. Users can extend this folder by adding their own samples to test the model’s adaptability.

**4. download.png**

A visualization of the model's trained results is provided in this file. It includes a sample of correctly and incorrectly classified digits, offering insights into the model’s performance.
