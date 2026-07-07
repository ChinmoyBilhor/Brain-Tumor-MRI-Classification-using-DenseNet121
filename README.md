# Brain Tumor MRI Classification using DenseNet121

## Overview
This project develops a deep learning model to classify brain MRI images into four categories using a pretrained DenseNet121 model with transfer learning. The model is implemented using PyTorch and includes data preprocessing, augmentation, training, and evaluation.

## Dataset
- Source: Kaggle Brain Tumor MRI Dataset
- Dataset Link: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset
- Classes:
  - Glioma
  - Meningioma
  - Pituitary Tumor
  - No Tumor

## Technologies Used
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pillow
- KaggleHub

## Project Workflow
- Dataset Exploration
- Data Preprocessing and Augmentation
- Train-Validation Split
- DenseNet121 Transfer Learning
- Model Training
- Model Evaluation

## Model Configuration
- Model: DenseNet121 (Pretrained)
- Transfer Learning: Yes
- Loss Function: CrossEntropyLoss
- Optimizer: Adam
- Learning Rate: 0.0001
- Learning Rate Scheduler: ReduceLROnPlateau
- Dropout: 0.3
- Batch Size: 32
- Epochs: 10
- Early Stopping: Patience = 5

## Evaluation Metrics
The model is evaluated using:
- Test Accuracy
- Classification Report
- Confusion Matrix
- Training Accuracy Curve
- Validation Accuracy Curve
- Training Loss Curve
- Validation Loss Curve

## Files
- Brain_Tumor_MRI_Classification_using_DenseNet121.ipynb – Complete project notebook
- README.md – Project documentation
- requirements.txt – Python dependencies

## Future Improvements
- Hyperparameter tuning
- Compare with ResNet50 and EfficientNet
- Deploy the model using Streamlit
- Add Grad-CAM for model interpretability

## Author
Chinmoy Bilhor
