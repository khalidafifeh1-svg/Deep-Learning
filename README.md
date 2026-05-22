# Deep Learning – White Blood Cell Classification

Overview

This project explores the classification of white blood cells from microscopic images using deep learning techniques. The aim is to automate haematological diagnosis by comparing multiple convolutional neural network architectures.

Three models were implemented and evaluated:

Custom CNN (BloodCellCNN)
ResNet-50 (Transfer Learning)
EfficientNet-B3 (Transfer Learning)

Objective

To accurately classify white blood cell types:

Neutrophils

Lymphocytes

Monocytes

Eosinophils

Dataset

Source: Kaggle Blood Cell Images

Total images: 12,500

Image size: 320 × 240

Classes: 4 white blood cell types

<img width="426" height="70" alt="dataset sample" src="https://github.com/user-attachments/assets/c1c2fae0-d309-4bcc-b138-63a37cff7b12" />

Models Used
1. Custom CNN (BloodCellCNN)
3 convolutional blocks
Fully connected layers
Baseline model
2. ResNet-50
Pre-trained on ImageNet
Transfer learning applied
Fine-tuned classifier
3. EfficientNet-B3
Advanced transfer learning model
Optimised architecture for accuracy and efficiency

Techniques Used
Data augmentation
Hyperparameter Tuning Results

<img width="445" height="115" alt="hyperparameter tuning results" src="https://github.com/user-attachments/assets/be1b9922-4e06-4b00-8d6d-dda0f99b7a43" />

Transfer learning
Gradient descent optimisation
Model evaluation using multiple metrics

Results
Model	Accuracy

BloodCellCNN	74.16%

ResNet-50	54.16%

EfficientNet-B3	98.94%

Best Model Performance

EfficientNet-B3 achieved the highest performance among all models.

<img width="433" height="137" alt="best model results" src="https://github.com/user-attachments/assets/cd5adf6f-8b15-4a5b-82d1-ed7720d66347" />

Key Insights

Transfer learning significantly improves performance

EfficientNet outperforms ResNet-50 and CNN baseline

Class overlap exists between Eosinophils and Neutrophils

Data augmentation improves generalisation

Technologies Used
Python

TensorFlow / Keras

Scikit-learn

NumPy

Pandas

Matplotlib
