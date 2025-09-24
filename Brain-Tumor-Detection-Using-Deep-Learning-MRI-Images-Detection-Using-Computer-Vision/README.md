# 🧠 Brain Tumor Detection Using Deep Learning (MRI Images)

## Overview
This project implements an **automated brain tumor detection system** using **deep learning techniques** on MRI scans. It accurately identifies the presence of brain tumors, assisting medical professionals in diagnosis and treatment planning.  

---

## How It Works
The system leverages **Convolutional Neural Networks (CNNs)** to analyze MRI images and classify tumor presence. Preprocessing steps like **image normalization, resizing, and augmentation** improve model performance, while visualization tools highlight the tumor regions for interpretability.

---

## Screenshots

### 1️⃣ Input and Prediction
![Input and Prediction](Screenshot 2025-09-24 130803.png)

The system takes MRI scans as input and predicts whether a tumor is present.  

### 2️⃣ Tumor Highlighted Output
![Tumor Highlighted](Screenshot 2025-09-24 130813.png)

The detected tumor area is highlighted for easier visualization and clinical interpretation.  

---

## Features
- **CNN-based Classification:** Detects tumors with high accuracy.  
- **Visualization:** Highlights tumor regions in MRI scans.  
- **Preprocessing:** Handles image normalization and augmentation.  
- **Evaluation Metrics:** Reports accuracy, precision, recall, and F1-score.  

---

## Installation & Usage
```bash
# Clone the repository
git clone <repo-url>
cd BrainTumorDetection

# Install dependencies
pip install -r requirements.txt

# Train the model
python train.py

# Test or evaluate
python evaluate.py
