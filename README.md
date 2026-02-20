# flower-classification-final-project
End-to-end deep learning project for multi-class flower image classification, including dataset preparation, CNN model development, training, and performance evaluation.

**🌸 Flower Image Classification using CNN**

Final Project – Machine Learning Programming – Conestoga College – Semester 1, 2025

**📌 Project Overview**

This project was developed as part of the final assessment for Machine Learning Programming. The objective was to design and implement an end-to-end deep learning pipeline for multi-class flower image classification.

The system processes image data, trains a Convolutional Neural Network (CNN), and evaluates model performance using standard classification metrics.

**🎯 Objectives**

Build a complete image classification pipeline

Perform dataset preprocessing and splitting

Train a CNN model using TensorFlow/Keras

Evaluate model performance on unseen data

Analyze training and validation behavior

**📂 Dataset**

Source: Public flower image dataset (via Hugging Face)

Type: Multi-class image classification

Categories: Multiple flower species (e.g., daisy, rose, tulip, etc.)

**The dataset was divided into:**
Training set
Validation set
Test set

**🛠 Methodology**
1️⃣ Data Preparation

Loaded dataset using the datasets library

Converted images into structured directory format

Created training, validation, and test splits

Normalized pixel values

2️⃣ Model Architecture

The model is a Convolutional Neural Network (CNN) implemented using TensorFlow/Keras, including:

Convolutional layers

MaxPooling layers

Fully connected (Dense) layers

Softmax output layer for multi-class classification

3️⃣ Training Configuration

Loss Function: Categorical Crossentropy

Optimizer: Adam

Evaluation Metric: Accuracy

📊 Results

Final Reportable Accuracy:

Best Validation Accuracy: 89.6%

Best Test Accuracy (VGG): 91.6%

The model demonstrates effective learning of image features. Minor differences between training and validation accuracy suggest potential overfitting, which could be improved with additional regularization or data augmentation.
