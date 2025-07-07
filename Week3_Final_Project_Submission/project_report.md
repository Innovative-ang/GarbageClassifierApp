# 📝 Project Report – Garbage Classification

## 📌 Problem Statement
Build an image classification model to identify the type of garbage for better waste management.

## 📂 Dataset
- Source: (https://www.kaggle.com/datasets/farzadnekouei/trash-type-image-dataset)
- Classes: Cardboard, Glass, Metal, Paper, Plastic, Trash.
- Preprocessing: Image resizing, normalization

## 🧠 Model Architecture
- Base Model: EfficientNetV2S
- Fine-tuned: Last 60 layers
- Loss Function: Focal Loss
- Optimization: Adam

## 🎯 Evaluation Metrics
- Accuracy: ~90%
- Confusion Matrix: Attached in train_model.ipynb file
- Class-wise Precision & Recall

## 🚀 Deployment
- Interface: Gradio
- Features: Upload image → Predict → Output label with confidence

## 🧩 Challenges & Solutions
- Class imbalance → Solved using focal loss + class weights
- Misclassifications in similar-looking items → Data augmentation used

## ✅ Conclusion
The model performs robustly on unseen data and is ready for real-world deployment.
