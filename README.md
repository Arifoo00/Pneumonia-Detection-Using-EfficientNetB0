# Pneumonia Detection Using EfficientNetV2B0

## Project Overview

This project presents a deep learning-based pneumonia detection system using Chest X-ray images and the EfficientNetV2B0 architecture with TensorFlow/Keras. The model classifies chest X-ray images into two categories: NORMAL and PNEUMONIA.

## Features

- Transfer Learning using EfficientNetV2B0
- Data Augmentation
- Fine-Tuning
- Binary Image Classification
- Early Stopping
- ReduceLROnPlateau
- Model Checkpoint
- Performance Evaluation

## Dataset

Dataset: Chest X-ray Pneumonia Dataset

Classes:
- NORMAL
- PNEUMONIA

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Model Performance

| Metric | Value |
|--------|-------|
| Validation Accuracy | 96.07% |
| Test Accuracy | 85.74% |
| Test AUC | 95.24% |
| Precision | 83.22% |
| Recall | 96.67% |

## Repository Structure

```
train.ipynb
README.md
requirements.txt
best_model.keras
training_history.csv
fine_tuning_history.csv
accuracy_curve.png
confusion_matrix.png
```

## Author

Arif Ali Khan

BS Computer Science

University of Peshawar

Pakistan
