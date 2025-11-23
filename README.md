# 🌿 Plant Disease Classification using CNNs

**Project:** Plant Disease Classification using ResNet-9 (Deep Learning)  
**Author:** Sparsh Saini  
**Notebook (local):** `/mnt/data/Plant Disease Classification using CNNs.ipynb`

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](#license)

---

## 🚀 Project Overview

This project trains a convolutional neural network (ResNet-9) to classify plant leaf diseases from images. The pipeline includes dataset cleaning & augmentation, model training with transfer learning, evaluation on a large dataset (~40K images), and a Streamlit web app for real-time inference by farmers and agronomists.

**Core outcomes**
- Trained ResNet-9 model for multi-class leaf disease classification  
- Achieved **96.4% accuracy** on a 40K+ image dataset (after augmentation & fine-tuning)  
- Built a Streamlit app for real-time, on-device image inference  

---

## 📌 Highlights / Key Features

- Data preprocessing: resizing, normalization, class balancing, augmentation (flip, rotation, color jitter).  
- Model: ResNet-9 with transfer learning (pretrained backbone), Adam optimizer, early stopping, and learning-rate scheduling.  
- Training: Stratified train/validation/test split, checkpointing, and metric logging.  
- Deployment: Streamlit app for real-time camera/upload-based inference; model exported with `torch.save()` or `joblib` for CPU inference.  
- Utilities: confusion matrix, classification report (precision/recall/F1), Grad-CAM visualization for interpretability.

---

## 📁 Suggested Repository Structure

