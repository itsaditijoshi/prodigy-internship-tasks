# Task 5 – Image Classification using CNN and Machine Learning

## ✨ Objective
To classify different types of garbage images into categories using two approaches:
- A **Convolutional Neural Network (CNN)**
- A **Machine Learning model**

## 🗂️ Dataset
We used the [Garbage Classification dataset by Gary Thung](https://www.kaggle.com/datasets/garythung/trashnet) available on **Kaggle**.

> 📌 To download the dataset:
> - Visit the link above.
> - Sign in to Kaggle.
> - Click “Download” to get the dataset.

## 🔍 Approach

### 1. CNN Model
- **Framework**: TensorFlow / Keras
- **Steps**:
  - Resize and normalize images
  - Apply data augmentation
  - Build CNN with Conv2D, MaxPooling, Flatten, Dense layers
  - Compile and train the model
  - Evaluate on test data

### 2. Machine Learning Model
- **Steps**:
  - Preprocess and extract features from images (HOG or raw pixel flattening)
  - Normalize and split data
  - Train ML models (like Random Forest, SVM, etc.)
  - Evaluate performance

## 📊 Results
CNN demonstrated higher classification accuracy compared to traditional ML models, especially in complex garbage categories.

## 💻 Technologies Used
- Python
- TensorFlow / Keras
- scikit-learn
- matplotlib, numpy, pandas

## 🔗 Dataset
**Kaggle Garbage Classification Dataset**:  
https://www.kaggle.com/datasets/garythung/trashnet
