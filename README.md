# CNN image classification

## Author

Milena Morawska

GitHub: https://github.com/MilenaMorawska

---

## Overview

This project covers the task of image classification using a custom convolutional neural network (CNN) trained from scratch. It provides tools for training and evaluating an image classifier across categories.

---

## Features
- Custom CNN built from scratch for image classification 
- Data augmentation pipeline 
- Regularisation techniques including SpatialDropout2D, standard Dropout, batch normalisation, and L2 regularisation
- Training callbacks for efficient, overfitting-resistant training
- Full evaluation suite: accuracy, precision, recall, F1-score, macro F1-score, and confusion matrices

---

## Dataset Setup

This project used a 10-class subset of an ImageNet-style image classification dataset. The dataset contains labelled images organised into separate class directories using ImageNet WordNet identifiers (e.g., `n02102040`).

The dataset is not included in this repository. To run the notebook:
- Obtain the dataset separately.
- Ensure images are organised into `train` and `val` directories.
- Update the `TRAIN_DIR` and `VAL_DIR` paths to match the dataset location.

---

## Requirements 

- Python 3.12
- TensorFlow
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Usage

The notebook was developed using Google Colab. If running in Colab, Google Drive mounting is required to access the dataset.
