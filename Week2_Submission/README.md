🗑️ Week 2 Submission – Garbage Classification Deployment with Gradio UI


🔍 Objective
In Week 2 of the AICTE Internship project, the focus was on model optimization and deployment. After training the garbage classification model, I created a Gradio web interface that allows users to upload images and get real-time predictions of garbage material.

✅ Tasks Completed in Week 2
📦 Switched to a lighter and faster model: EfficientNetV2B0

⚖️ Implemented Focal Loss to handle class imbalance more effectively

🔁 Fine-tuned deeper layers of the model for improved accuracy

📉 Applied Class Weights, Early Stopping, and ReduceLROnPlateau to stabilize training

📷 Built a Gradio UI for uploading garbage images and getting material predictions

📊 Plotted Accuracy & Loss Graphs over the training epochs

🔍 Displayed Confusion Matrix to evaluate class-wise prediction performance

💡 Optimized CPU usage (optionally disabled GPU and tuned thread usage)

🌐 Used inbrowser=True to launch the Gradio app directly in a browser

🧪 Final model achieved ~90%+ validation accuracy

⚙️ Deployment & UI
✅ Interface Built Using: Gradio

📤 Users Can:
→ Upload garbage images (plastic, glass, metal, etc.)
→ Get real-time prediction of the material type
→ View the confidence (accuracy) score


🔁 Why I Used EfficientNetV2B0 Instead of EfficientNetV2B2
✅ B0 is faster to train and uses less memory

💻 Well-suited for CPU-only environments (like my laptop)

📊 Still achieved ~90%+ accuracy with our small dataset


📈 Model Evaluation
📊 Accuracy & Loss Graphs
→ Show training progress and validation trends over epochs
→ Help visualize model learning and convergence

📉 Confusion Matrix
→ Displays prediction performance per class
→ Highlights which classes were misclassified and helps refine the model


⚙️ Ideal for deployment and speed without requiring GPU resources


🧪 Final Notes
🔧 Model File Used:
efficientnetv2b0_garbage_classifier_fixed.h5 (saved after fine-tuning)

📓 Notebook File:
train_model.ipynb includes full pipeline – from training to deployment

