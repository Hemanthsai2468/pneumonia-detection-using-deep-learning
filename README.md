# Pneumonia Detection Project 🫁

This project uses a deep learning pipeline to detect **Pneumonia** in chest X-ray images using Convolutional Neural Networks (CNNs).

## 🔍 Dataset
Dataset: Chest X-Ray Images (Pneumonia)  
Source: [Kaggle - Paultimothymooney Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

## 📊 Features
- Image preprocessing and normalization
- Data loading using `ImageDataGenerator`
- CNN Model Architecture (Conv2D, MaxPooling, Dense)
- Model Evaluation:
  - Accuracy
  - Precision
  - Recall
  - Loss Curve Visualization

## 📈 Output
- Accuracy/Loss plots across epochs  
- Final model accuracy ~95%  
- Binary classification: **Pneumonia** vs **Normal**

## 📦 Libraries Used
- tensorflow / keras
- numpy
- matplotlib
- seaborn
- sklearn

## ⚙️ Usage
```bash
jupyter notebook pneumonia_detection.ipynb
