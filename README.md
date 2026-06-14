# CNN CIFAR10 Classification

## Overview  
This notebook demonstrates how to build, train, and evaluate a simple Convolutional Neural Network (CNN) to classify images from the CIFAR10 dataset. The model architecture includes convolutional layers followed by dense layers for classification. Training experiments cover different epochs and kernel sizes with performance visualization.

## Features  
- Load and preprocess CIFAR10 dataset  
- Visualize sample images with labels  
- Build a CNN with Conv2D, MaxPooling, Flatten, and Dense layers  
- Train the model with varying epochs (3, 10, 20, 50)  
- Evaluate model accuracy and plot training history  
- Display confusion matrix for model predictions  
- Experiment with different convolution kernel sizes (3x3 vs 5x5)  
- Analyze impact of training epochs and kernel size on accuracy  

## Tech Stack  
- Python 3  
- Jupyter Notebook / Google Colab  
- TensorFlow (Keras API)  
- Matplotlib  
- scikit-learn (for confusion matrix)  

## How to Use  
1. Clone or download the repository.  
2. Open the notebook `cnn-cifar10-classification.ipynb` in Jupyter or Google Colab.  
3. Run cells sequentially to train and evaluate the CNN model.  
4. Modify the number of epochs or kernel size in the model definition as desired.  
5. Observe training graphs, accuracy, and confusion matrix outputs.  

## Status  
The notebook is well-organized and formatted for clear presentation on GitHub, suitable for educational and experimental purposes.