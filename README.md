# 🧠 CNN Image Classifier with TensorFlow 🖼️

This project builds and trains a Convolutional Neural Network (CNN) using TensorFlow to classify images from the [Fashion MNIST dataset](https://github.com/zalandoresearch/fashion-mnist).

## 📂 Project Structure

cnn-fashion-mnist-tensorflow/
├── cnn-fashion-mnist.ipynb # Jupyter Notebook with full model pipeline
├── requirements.txt # Dependencies
├── README.md # Project overview



## 🧪 Model Overview

- **Architecture:** 3 Convolutional blocks + Dense layers
- **Loss:** `categorical_crossentropy`
- **Optimizer:** Adam (`lr=0.0001`)
- **Regularization:** L2
- **Test Accuracy:** ~92%

## 📈 What You'll Learn

- How to load and preprocess Fashion MNIST
- Building deep CNNs using TensorFlow / Keras
- Visualizing model performance
- Evaluating prediction accuracy and loss curves

## 🚀 Run it Locally

```bash
git clone https://github.com/Ak1ra777/cnn-fashion-mnist-tensorflow.git
cd cnn-fashion-mnist-tensorflow
pip install -r requirements.txt
jupyter notebook cnn-fashion-mnist.ipynb



