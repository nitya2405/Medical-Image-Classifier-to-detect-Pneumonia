# 🧠 Medical Image Diagnosis using Convolutional Neural Networks (CNNs)

## Overview
Medical imaging plays a critical role in early diagnosis and treatment planning. This project develops and evaluates multiple **CNN-based models** to classify medical images, focusing not only on performance but also on interpretability and clinical relevance.

Both **custom-built CNNs** and **pretrained architectures** are explored to understand trade-offs between accuracy, generalization, and computational cost.

---

## Problem Statement
Given medical images, the objective is to accurately classify them into diagnostic categories while ensuring model decisions are explainable and trustworthy for clinical use.

---

## Project Workflow

### 🖼️ Image Processing
- Image resizing and normalization  
- Data augmentation to reduce overfitting  
- Train / validation / test dataset split  

### 🤖 Model Architectures
- Custom CNN architecture  
- ResNet (transfer learning)  
- VGG (transfer learning)

Pretrained models are fine-tuned to adapt to the medical imaging domain.

---

### 📊 Evaluation & Validation
- Accuracy  
- Confusion Matrix  
- Sensitivity (Recall for positive cases)  
- Specificity  
- ROC–AUC curves  

Performance is analyzed across datasets to ensure generalization.

---

### 🔍 Interpretability
- Grad-CAM visualizations  
- Heatmaps highlighting regions influencing predictions  
- Qualitative analysis of model focus areas

This helps bridge the gap between black-box models and clinical trust.

---

## Tech Stack
- Python  
- TensorFlow / PyTorch  
- Scikit-learn  
- OpenCV / PIL  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## Setup & Execution

```bash
git clone https://github.com/<YourName>/<RepoName>.git
cd <RepoName>
pip install -r requirements.txt
jupyter notebook
