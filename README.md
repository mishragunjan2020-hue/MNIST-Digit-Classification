# MNIST-Digit-Classification
Deep Learning model to classify hand-written digits using Keras/TensorFlow.
# MNIST Digit Classification using Neural Networks

## 📌 Overview
This project builds a Deep Neural Network using TensorFlow and Keras to accurately classify handwritten digits (0-9) from the standard MNIST dataset.

## 📊 Model Architecture
- **Input Layer:** Flatten (28x28 to 784)
- **Hidden Layer 1:** Dense (128 units, ReLU activation)
- **Hidden Layer 2:** Dense (64 units, ReLU activation)
- **Output Layer:** Dense (10 units, Softmax activation)

## 🎯 Results
- **Training Accuracy:** ~98.5%
- **Test Accuracy:** 97.94%
- **Optimizer:** Adam
- **Loss Function:** Sparse Categorical Crossentropy

## 🚀 How to Run
1. Open the `MNIST_Digit_Classification.ipynb` notebook in Google Colab.
2. Run all cells sequentially to train and evaluate the model.
