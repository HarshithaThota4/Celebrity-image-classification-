# Celebrity-image-classification-
This project is an end-to-end deep learning pipeline for **celebrity image classification**, developed using Python and Keras/TensorFlow. The notebook includes data preprocessing, CNN model building, training, evaluation, and prediction steps for multi-class image classification.

---

## 📘 Project Overview

This project performs **celebrity image classification** using a convolutional neural network (CNN). The dataset consists of **5 celebrity classes**, and the task is to correctly classify images into one of these categories.

The notebook follows these main steps:

1. **Data Loading & Preprocessing**
   - Images are read using OpenCV.
   - Haar cascades are used to detect and crop faces.
   - Images are resized and normalized.

2. **Exploratory Data Analysis**
   - Image samples are visualized.
   - Dataset class distribution is shown.

3. **Model Building**
   - A CNN model is constructed using Keras with layers like Conv2D, MaxPooling, Dropout, Flatten, and Dense.
   - The model is compiled using the Adam optimizer and categorical crossentropy loss.

4. **Model Training**
   - The model is trained on the preprocessed dataset with validation.

5. **Model Evaluation**
   - Accuracy and loss are plotted.
   - The model is evaluated on test data.
   - Predictions are made and visualized for sample test images.

---


## 🔧 Requirements

Make sure you have the following installed:

- Python 3.x
- Jupyter Notebook
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- OpenCV (if used for image processing)
---

## 📈 Results

- Accuracy Achieved: approx 90%
---

## 📚 References

- TensorFlow / Keras Documentation
- Deep Learning with Python – François Chollet

---
