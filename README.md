# image-classification-cnn-vs-mlp

##  Project Overview

This project focuses on image classification using Deep Learning techniques.
We compare the performance of a Multi-Layer Perceptron (MLP) and a Convolutional Neural Network (CNN) on a fruit image dataset.

The goal is to understand how different neural network architectures perform on image data.

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn

---

##  Dataset

* Fruits Image Dataset you can download it from : https://drive.google.com/drive/folders/1UXXGk_4_FIv0KJMCZT6vvfBrYXmk5mMR?usp=d
rive_link
* Training and Testing folders with multiple fruit classes
* Images resized to **64x64 pixels**

---

## ⚙️ Data Preprocessing

* Rescaled pixel values (1/255 normalization)
* Loaded data using `ImageDataGenerator`
* Created training and validation datasets

---

##  Models Implemented

### 🔹 1. MLP (Multi-Layer Perceptron)

* Flatten input layer
* Dense layers with ReLU activation
* Batch Normalization
* Dropout for regularization
* Softmax output layer

###  2. CNN (Convolutional Neural Network)

* Convolutional layers with ReLU
* MaxPooling layers
* Batch Normalization
* Dropout layers
* Fully connected dense layer
* Softmax output layer

---

##  Training Details

* Optimizer: Adam
* Loss Function: Categorical Crossentropy (with label smoothing)
* Early Stopping used to prevent overfitting
* Models trained on training data and validated on test data

---

##  Results & Evaluation

* Compared both models based on:

  * Accuracy
  * Loss
  * Training Time

* Generated:

  * Accuracy & Loss graphs
  * Confusion Matrix

 CNN performed better than MLP for image classification tasks.

---

##  Visualizations

* Training vs Validation Accuracy
* Training vs Validation Loss
* Confusion Matrix

---

##  Key Learnings

* CNNs are more effective for image data than MLPs
* Regularization techniques (Dropout, BatchNorm) improve performance
* Early stopping helps prevent overfitting
  
---

##  Author

* Sneha SInghal

---

##  If you like this project

Give it a star on GitHub!
