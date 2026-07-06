# 🛰️ EuroSAT Land Cover Classification using ResNet50

A deep learning project that classifies satellite images into **10 land cover categories** using **Transfer Learning** with **ResNet50** and **PyTorch**.

---

## 📖 Project Overview

This project uses the **EuroSAT RGB** dataset and a pretrained **ResNet50** model to classify satellite images into different land cover classes such as forests, rivers, residential areas, highways, and more.

Instead of training a convolutional neural network from scratch, Transfer Learning is used to leverage features learned from the ImageNet dataset, resulting in faster training and high classification performance.

This project was developed in **Google Colab** using **PyTorch** and serves as my first end-to-end computer vision project.

---

## 📊 Project Results

The model was trained using **Transfer Learning with ResNet50** on the **EuroSAT RGB** dataset. After 10 epochs of training, the model achieved the following performance:

| Metric | Result |
|:-------|:------:|
| 🧠 Model | ResNet50 (Transfer Learning) |
| 📦 Framework | PyTorch |
| 🛰️ Dataset | EuroSAT RGB |
| 🗂️ Classes | 10 |
| 🖼️ Total Images | 27,000 |
| 🎯 Training Accuracy | **94.61%** |
| ✅ Test Accuracy | **93.70%** |
| 📈 Weighted F1-Score | **0.94** |

> **Summary:** The model achieved strong generalization on unseen satellite images, obtaining **93.70% test accuracy** and a **0.94 weighted F1-score** across all 10 land-cover classes.

---

## ✨ Key Features

- Transfer Learning using ResNet50
- Multi-class satellite image classification
- PyTorch implementation
- Data preprocessing and augmentation pipeline
- Model evaluation using Accuracy, Precision, Recall and F1-score
- Confusion Matrix and error analysis
- Google Colab compatible

---

## 🔄 Project Workflow

 <img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/32d79c49-e752-4b36-be83-e7f99a76bc33" />

# 🖼️ Project Showcase

## Dataset Sample

 <img width="1203" height="990" alt="Sample Predictions" src="https://github.com/user-attachments/assets/aeef62ea-e63f-45c3-b095-43533a6055e6" />

## Class Distribution

<img width="859" height="558" alt="EuroSAT Class distribution" src="https://github.com/user-attachments/assets/7f089ecf-fde0-4f05-87b3-365bf5ccb5d6" />

## Confusion Matrix

<img width="932" height="808" alt="Confusion Matrix   Predictions" src="https://github.com/user-attachments/assets/26e8bea1-3509-4c89-a12d-ed6a05ec57ca" />

## Sample Predictions

<img width="1203" height="990" alt="Sample Predictions" src="https://github.com/user-attachments/assets/1f909d6b-cbd1-4485-95aa-d84c4e5dc434" />

## Misclassified Images

<img width="1191" height="985" alt="Misclassified Test Images" src="https://github.com/user-attachments/assets/95b7a8ad-6d92-4c97-b2b1-f1cdd9a87908" />
