# 🧠 Brain Tumor Detection using Deep Learning (VGG16)

A deep learning project focused on automated brain tumor classification and detection using MRI scans. This repository utilizes a fine-tuned **VGG16** convolutional neural network architecture to accurately classify brain scans into four distinct categories: **Glioma, Meningioma, Pituitary tumor, and No Tumor**.

---

## 📊 Dataset & Exploratory Analysis
The dataset contains structural brain MRI scans categorized across the target classes. 

### 1. Types of Tumors & Sample Views
<p align="center">
  <img src="results/types_of_tumor.png" width="80%" alt="Types of Tumor">
</p>
<p align="center">
  <img src="results/types_of_tumor_from_diff_angles.png" width="80%" alt="Types of Tumor from Different Angles">
</p>

### 2. Dataset Distributions
<p align="center">
  <img src="results/Class Distribution of training data.png" width="45%" alt="Class Distribution of Training Data">
  <img src="results/training_and_testing_data_distribution.png" width="45%" alt="Training and Testing Data Distribution">
</p>

---

## ⚙️ Model Architecture & Training
Feature extraction and training progress over 25 epochs:
<p align="center">
  <img src="results/Convolution_feature_maps.png" width="80%" alt="Convolution Feature Maps">
</p>
<p align="center">
  <img src="results/Training Accuracy & Loss Over 25 Epochs.png" width="75%" alt="Training Accuracy and Loss">
</p>

---

## 📈 Evaluation & Performance Metrics

### 1. Confusion Matrix
<p align="center">
  <img src="results/confusion_matrix.png" width="60%" alt="Confusion Matrix">
</p>

### 2. Classification Reports & Performance
<p align="center">
  <img src="results/classification_report.png" width="65%" alt="Classification Report">
  <img src="results/per-class_classification_report.png" width="65%" alt="Per-Class Classification Report">
</p>

---

## 💡 Sample Predictions & Inference
<p align="center">
  <img src="results/result1.png" width="45%" alt="Result 1">
  <img src="results/result2.png" width="45%" alt="Result 2">
</p>

---

## 🚀 Getting Started

### Prerequisites
Install the required dependencies:
```bash
pip install tensorflow keras numpy pandas matplotlib seaborn scikit-learn
