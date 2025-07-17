# Task 4 – Image Classification using CNN and Machine Learning

## ✨ Objective
To classify flowers into different categories using two approaches:
- A **Convolutional Neural Network (CNN)**
- A **Machine Learning model**

## 🗂️ Dataset
We used the [Flowers Recognition dataset by Telkom Indonesia](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition) available on **Kaggle**.

> 📌 To download the dataset:
> - Go to the link above.
> - Sign in to Kaggle.
> - Click “Download” to get the dataset.

## 🔍 Approach

### 1. CNN Model
- **Framework**: TensorFlow / Keras
- **Steps**:
  - Image resizing
  - Data augmentation
  - CNN model creation (Conv2D, MaxPooling, Flatten, Dense)
  - Model training and evaluation

### 2. Machine Learning Model
- **Steps**:
  - Convert images to grayscale or flatten RGB values
  - Feature extraction (HOG or raw pixels)
  - Train-test split
  - Classification using models like Random Forest or SVM

## 📊 Results
CNN delivered better classification performance and accuracy than the traditional ML models.

## 💻 Technologies Used
- Python
- TensorFlow / Keras
- scikit-learn
- matplotlib, numpy, pandas

## 🔗 Dataset
**Kaggle Flowers Recognition**:  
https://www.kaggle.com/datasets/alxmamaev/flowers-recognition
