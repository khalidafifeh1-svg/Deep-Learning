# Deep-Learning

Overview
This project explores the classification of white blood cells from microscopic images using deep learning. The goal is to automate haematological diagnosis by comparing multiple convolutional neural network architectures.
Three models were implemented and evaluated:
Custom CNN (BloodCellCNN)
ResNet-50 
EfficientNet-B3 

Objective
To accurately classify white blood cell types:
Neutrophils
Lymphocytes
Monocytes
Eosinophils
using deep learning and evaluate model performance.

Dataset
Source: Kaggle (microscopic WBC images)
Total images: 12,444
Image size: 320 × 240
Classes: 4 white Blood cell types
<img width="426" height="70" alt="image" src="https://github.com/user-attachments/assets/c1c2fae0-d309-4bcc-b138-63a37cff7b12" />

Models Used
1. Custom CNN 
3 convolutional blocks
Fully connected layers
Baseline model

2. ResNet-50
Pre-trained on ImageNet
Transfer learning applied
Fine-tuned classifier
3. EfficientNet-B3
Advanced transfer learning model
Scaled architecture for efficiency and accuracy

Techniques Used
Data augmentation
Transfer learning
Hyperparameter tuning 
<img width="445" height="115" alt="image" src="https://github.com/user-attachments/assets/be1b9922-4e06-4b00-8d6d-dda0f99b7a43" />
Gradient descent optimisation
Model evaluation with multiple metrics

Result 
| Model           | Accuracy   |
| --------------- | ---------- |
| BloodCellCNN    | 74.16%     |
| ResNet-50       | 54.16%     |
| EfficientNet-B3 | **98.94%** |

Best Model
<img width="433" height="137" alt="image" src="https://github.com/user-attachments/assets/cd5adf6f-8b15-4a5b-82d1-ed7720d66347" />

Key Insights
Transfer learning significantly improves performance
EfficientNet outperforms ResNet and custom CNN
Class overlap exists between Eosinophils and Neutrophils
Data augmentation improves generalisation

Technologies
Python
TensorFlow / Keras
Scikit-learn
NumPy / Pandas
Matplotlib
