MalaScan: Automated Malaria Detection Using Deep Learning
Overview
This project implements an automated malaria detection system using deep learning on grayscale blood smear images. The model preprocesses, augments, and classifies cells as infected or uninfected using a Convolutional Neural Network (CNN) in TensorFlow.

Dataset
Source: Cell Images for Detecting Malaria (Kaggle)

Note: The dataset is not included in this repository. Please download it directly from Kaggle.

Preprocessing
Converted all images in the training folder to grayscale.

Resized images to 132x132 pixels based on the average dimensions of the dataset.

Training & Augmentation
Applied extensive data augmentation (random rotations, shifts, flips, zoom, etc.) to increase dataset diversity and improve generalization.

Trained a custom CNN model on the preprocessed and augmented images using TensorFlow/Keras.

Regularization techniques such as dropout and batch normalization were used to prevent overfitting and enhance model robustness.

The model demonstrated high accuracy and strong generalization to unseen data, supporting rapid and reliable malaria screening.

Usage
Download the dataset from Kaggle and extract it locally.

Open the provided Google Colab notebook (.ipynb).

Upload the dataset to your Google Drive and update the paths in the notebook as needed.

Run the notebook to perform preprocessing, augmentation, model training, and evaluation.

Requirements
Python 3.x

TensorFlow

Keras

NumPy

Matplotlib
