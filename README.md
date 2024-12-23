# Image Classification on Fashion MNIST with TensorFlow Quantum and Cirq

## Overview
This project demonstrates how to perform image classification on the Fashion MNIST dataset using Quantum Machine Learning (QML) techniques with TensorFlow Quantum and Cirq. The goal is to classify images of sandals and ankle boots using a quantum neural network (QNN).
This Repository contains implementation of Quantum Neural Network as well as Classical Convolutional Neural Network for Classification Task on the popular Fashion MNIST dataset.
For the Quantum Implementation, TensorFlow-Quantum and Cirq are used.For the Classical Implementation, TensorFLow and TensorBoard are used.The Repository contains weights for trained Classical and Quantum Models.


## About the Dataset
The Fashion MNIST dataset is a collection of 70,000 grayscale images of clothing items, each labeled with one of 10 classes. For this project, we focus on two classes:
- **5**: Sandal
- **9**: Ankle boot

We will downscale the images from their original size of (28, 28) to (2, 2) to accommodate the limitations of quantum hardware.

## Requirements
To run this project, you need to have the following packages installed:
- TensorFlow 2.17.0
- TensorFlow Quantum
- Cirq
- NumPy
- Matplotlib
- Scikit-learn


## Steps Involved
1. **Data Preparation**: Load the Fashion MNIST dataset and filter it to include only the classes of interest (sandal and ankle boot).
2. **Preprocessing**: Normalize the image data and downscale the images to (2, 2).
3. **Data Encoding**: Convert the pixel values to binary encoding suitable for quantum circuits.
4. **Quantum Circuit Creation**: Create quantum circuits from the encoded images.
5. **Quantum Neural Network (QNN)**: Build and train a QNN using the created circuits.
6. **Model Evaluation**: Evaluate the model's performance on the test dataset.
7. **Visualization**: Visualize the training results, including accuracy and loss.

## Usage
To run the project, open the Jupyter notebook and execute the cells sequentially. Ensure that you have the required packages installed and that your environment supports TensorFlow Quantum.


## References
- [TensorFlow Quantum Tutorials](https://www.tensorflow.org/quantum/tutorials)
- [Cirq Documentation](https://quantumai.google/cirq)

