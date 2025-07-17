# Task 3 – Image Classification using CNN and Machine Learning

## ✨ Objective
To classify images into various categories using two different approaches:
- A Convolutional Neural Network (CNN)
- A Machine Learning model

## 🗂️ Dataset
We used the [Intel Image Classification dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification) available on **Kaggle**.

> 📌 To download the dataset:
> - Visit the link above.
> - Sign in to Kaggle.
> - Click “Download”.

The dataset includes 6 classes: `buildings`, `forest`, `glacier`, `mountain`, `sea`, and `street`.

## 🔍 Approach

### 1. CNN Model
- Framework: TensorFlow / Keras
- Steps:
  - Image resizing and normalization
  - Data augmentation (optional)
  - CNN model creation (Conv2D, MaxPooling, Flatten, Dense)
  - Model training, evaluation, and prediction

### 2. Machine Learning Model
- Steps:
  - Feature extraction from images (using techniques like HOG or flattening)
  - Preprocessing (e.g., grayscale conversion, scaling)
  - Classification using models like Random Forest, SVM, or Logistic Regression

## 📊 Results
CNN achieved higher accuracy due to its ability to learn spatial features from image data.  
Traditional ML models performed reasonably well after proper feature extraction.

## 💻 Technologies Used
- Python
- TensorFlow / Keras
- scikit-learn
- OpenCV
- numpy, pandas, matplotlib

## 🔗 Dataset
**Kaggle – Intel Image Classification**:  
https://www.kaggle.com/datasets/puneet6060/intel-image-classification
