# Convolutional Neural Network for MNIST Classification

## 📌 Overview
This project implements a **Convolutional Neural Network (CNN)** to classify handwritten digits from the **MNIST dataset**. The MNIST dataset consists of **60,000 training images** and **10,000 test images**, each representing digits from 0 to 9 in 28x28 grayscale format. The CNN is designed to achieve high accuracy in digit classification through deep learning techniques.

## 🚀 Features
- **Preprocessing:** Normalization and reshaping of MNIST images.
- **CNN Architecture:** Multi-layer convolutional network with pooling and dropout.
- **Training & Validation:** Model trained on MNIST dataset with performance evaluation.
- **Performance Metrics:** Accuracy, loss, and confusion matrix visualization.
- **Easy to Use:** Simple implementation with TensorFlow/Keras.

## 🛠️ Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- scikit-learn

You can install the required dependencies using:
```bash
pip install tensorflow keras numpy matplotlib scikit-learn
```

## 📂 Dataset
The MNIST dataset is automatically downloaded when using TensorFlow/Keras. No manual download is required.

## Architecture
The CNN model consists of the following layers:
1. **Conv2D** - Extracts features using a 3x3 filter.
2. **MaxPooling2D** - Reduces spatial dimensions (2x2 pool size).
3. **Conv2D** - Another convolutional layer to learn deeper features.
4. **MaxPooling2D** - Further spatial reduction.
5. **Flatten** - Converts feature maps into a 1D vector.
6. **Dense (Fully Connected Layer)** - Final classification using Softmax activation.

## 📊 Results
- Achieves **98%+ accuracy** on the MNIST test set.
- Loss and accuracy plots provided for training analysis.
- Confusion matrix for detailed performance insights.
