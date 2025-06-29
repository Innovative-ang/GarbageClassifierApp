# 🗑️ Week 2 Submission – Garbage Classification Deployment with Gradio UI

🔍 **Objective**  
In Week 2, the focus was on model optimization and deployment. After training the garbage classification model, I created a Gradio web interface to allow users to upload images and get real-time predictions of garbage material.

---

## ✅ Tasks Completed in Week 2

- 📦 Switched to a lighter and faster model: **EfficientNetV2B0**  
- ⚖️ Implemented **Focal Loss** to handle imbalanced classes  
- 🔁 Fine-tuned deeper layers for better accuracy  
- 📉 Added class weights, early stopping, and LR scheduling  
- 📷 Created a **Gradio UI** for uploading and predicting material  
- 📊 Plotted **Accuracy & Loss Graphs** over epochs  
- 🔍 Displayed **Confusion Matrix** to evaluate class-wise performance  
- 💡 Optimized CPU usage (optional GPU disabling)  
- 🌐 Used `inbrowser=True` to launch the app directly in browser  
- 🧪 Final model achieved ~90%+ validation accuracy  

---

## ⚙️ Deployment & UI

- Used **Gradio** for an interactive web interface  
- Upload garbage images → see material type + confidence score  
- Easy to test in browser via notebook  

---

## 🔁 Why I used EfficientNetV2B0 instead of EfficientNetV2B2

- ✅ B0 trains faster, uses less memory, and suits my CPU-based laptop  
- 📊 Still gives high accuracy (~90%) for our small dataset  
- ⚙️ Best choice for deployment & speed without needing a GPU  

---

## 📈 Model Evaluation

- **📊 Accuracy & Loss Graphs:**  
  Shows steady training progress and model convergence  

- **📉 Confusion Matrix:**  
  Visual breakdown of predictions per class to spot misclassifications  

- **⚙️ Ideal for deployment and speed without requiring GPU resources**
- **🧪 Final Notes 🔧 Model File Used: efficientnetv2b0_garbage_classifier_fixed.h5 (saved after fine-tuning)**
- **📓 Notebook File: train_model.ipynb includes full pipeline – from training to deployment **
