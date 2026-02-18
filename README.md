Handwritten Character & Digit Recognition using CNN
====================================================
This project builds a Convolutional Neural Network (CNN) that recognizes handwritten:
Digits (0–9)
Uppercase letters (A–Z)
Lowercase letters (a–z)
using the EMNIST dataset.

Features
--------
Deep learning-based image classification
Supports 62 handwritten characters
Training accuracy around ~90%
Confusion matrix and evaluation metrics included
Real handwritten image prediction demo
Saved reusable trained model

Tech Stack
----------
Python
TensorFlow / Keras
NumPy, Matplotlib, Seaborn
TensorFlow Datasets (EMNIST)

Project Workflow
----------------
Load and preprocess EMNIST dataset
Normalize and reshape images for CNN
Train CNN model for 62-class classification
Evaluate using accuracy, confusion matrix, F1-score
Predict custom handwritten images
Save trained model for reuse

How to Run
-----------
pip install -r requirements.txt

Open the notebook and run all cells.

Applications
-------------
Optical Character Recognition (OCR)
Bank cheque and postal code reading
Digitizing handwritten documents
Assistive technology for visually impaired users



