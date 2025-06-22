# 🗑️ Week 1 Submission – Garbage Classification using EfficientNet

## 🔍 Objective
In Week 1 of the AICTE Internship project, I developed the base model for a deep learning-based **Garbage Classification System**. The objective is to classify garbage images into categories like cardboard, glass, metal, paper, plastic, and trash using a Convolutional Neural Network (CNN) with EfficientNet.

---

## ✅ Tasks Completed in Week 1

- 📁 Collected and preprocessed the dataset (from Kaggle).
- 🧠 Built an image classification model using **EfficientNetV2B2**.
- 🏗️ Added custom layers and compiled the full model.
- 🏋️ Trained the model using the dataset with validation.
- 📂 Implemented an image upload feature to test predictions.
- 📊 Predicted the garbage material type along with confidence score.
- 💾 Saved the trained model (`efficientnet_garbage_classifier.h5`).
- 📓 Documented the full process in `train_model.ipynb`.

---

## ⚙️ Image Upload Feature

- Users can **upload an image of garbage**, and the system predicts the **material type** (e.g., plastic, metal) with **accuracy/confidence score**.
- Implemented using:
  - Gradio (for web interface) *or*
  - IPython Widgets (for Jupyter testing)

## For Dataset

The dataset used for this project is originally from Kaggle:  
🔗 [Garbage Classification Dataset](https://www.kaggle.com/datasets/farzadnekouei/trash-type-image-dataset).

After downloading, unzip the dataset folder to `TrashType_Image_Dataset` and place it in the project directory.
