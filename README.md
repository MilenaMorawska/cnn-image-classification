# CNN image classification & sentiment analysis

## Author

Milena Morawska

GitHub: https://github.com/MilenaMorawska

---

## Overview

This project covers the task of image classification using a custom convolutional neural network (CNN) trained from scratch. It provides tools for training and evaluating an image classifier across 10 categories.

---

## Features
- Custom CNN built from scratch for 10-class image classification 
- Data augmentation pipeline 
- Regularisation techniques including SpatialDropout2D, standard Dropout, batch normalisation, and L2 regularisation
- Training callbacks for efficient, overfitting-resistant training
- Full evaluation suite: accuracy, precision, recall, F1-score, macro F1-score, and confusion matrices

---

## Dataset Setup

The dataset is not included in this repository. 

This notebook was developed using Google Colab and loads the dataset from Google Drive. To run the notebook, the dataset must be downloaded separately and the file paths updated accordingly.

Before running the notebook:
- Ensure the dataset is available locally or in Google Drive.
- Update the `TRAIN_DIR` and `VAL_DIR` variables in the notebook to point to the correct dataset locations.

---

## Requirements 

- Python 3.12
- TensorFlow
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
and is not included in this repository due to file size and licensing restrictions.
