# Brain Tumor MRI Classification using CNNs and EfficientNet

## Overview
This project focuses on classifying Brain Tumor MRI scans using Deep Learning and Computer Vision techniques.

What initially started as a simple CNN experiment slowly evolved into a much larger project involving:
- Transfer Learning
- Fine-Tuning
- Medical Image Classification
- Explainable AI concepts

The project uses MRI scan images to classify brain tumors into 4 categories:
- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

---

## Dataset
Kaggle Brain Tumor MRI Dataset

Dataset contains:
- Training images
- Testing images
- MRI scans categorized into 4 tumor classes

---

## Project Pipeline

### 1. CNN from Scratch
Initially implemented a CNN manually using:
- Conv2D Layers
- MaxPooling Layers
- Dense Layers
- Dropout
- Data Augmentation

Although the model performed reasonably well, validation accuracy was not highly stable.

---

### 2. Transfer Learning using EfficientNetB0
To improve performance, EfficientNetB0 pretrained on ImageNet was implemented using TensorFlow/Keras.

Techniques used:
- Feature Extraction
- Transfer Learning
- Fine-Tuning pretrained layers
- Learning Rate Optimization
- EarlyStopping
- ModelCheckpoint

This significantly improved the model performance.

---

## Current Results
- Validation Accuracy: ~91%
- Stable MRI prediction pipeline implemented
- Saved trained models using `.keras`

---

## Explainable AI
Currently working on implementing Grad-CAM visualization to highlight tumor-focused regions in MRI scans and improve model interpretability.

---

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib

---

## Project Features
✔ CNN implemented from scratch  
✔ EfficientNetB0 Transfer Learning  
✔ Fine-Tuning pretrained layers  
✔ MRI preprocessing and augmentation  
✔ Model saving/loading  
✔ Prediction pipeline for MRI scans  
✔ Grad-CAM integration (in progress)

---

## What I Learned
Through this project, I gained hands-on exposure to:
- Transfer Learning
- Feature Extraction
- Fine Tuning
- CNN Architectures
- Overfitting vs Generalization
- Learning Rate Tuning
- Medical Image Classification
- Explainable AI concepts
- Model Saving and Checkpointing

---

## Future Improvements
- Complete Grad-CAM implementation
- Improve preprocessing pipeline
- Deploy using Streamlit
- Experiment with larger EfficientNet variants

---

## Acknowledgement
Special thanks to my friends Tanish and Aahana for helping with some of the research aspects and discussions around explainability techniques and medical imaging workflows.
