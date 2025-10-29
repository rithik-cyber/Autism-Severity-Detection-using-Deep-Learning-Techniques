# Autism-Severity-Detection-using-Deep-Learning-Techniques
A Computer Vision system that analyzes facial features using segmentation and landmark-based deep learning to assist early-stage autism screening.  
Built with medical-grade model design principles and explainability for clinician trust.

---

## 🎯 Objective

Autism diagnosis often requires manual behavioral assessment which can be slow and subjective.  
This project aims to support screenings by:

Extracting neurodevelopmental facial biomarkers  
 Highlighting regions of interest using segmentation + XAI  
 Providing interpretable confidence scores to clinicians

---

## 🚀 Key Features

- UNet-based semantic segmentation for facial region isolation  
- CNN classifier trained on extracted segment masks  
- **89% IoU** for segmentation performance  
- Explainable AI (Grad-CAM) for clinical interpretability  
- End-to-end pipeline from preprocessing → segmentation → classification  
- Streamlined to support real-world healthcare workflows

---

## 🧠 Technical Architecture

1️⃣ Image preprocessing + facial landmark extraction  
2️⃣ UNet segmentation to isolate relevant regions  
3️⃣ CNN classification on extracted features  
4️⃣ Explainability module for human-interpretable predictions  
5️⃣ Evaluation with medical-aligned metrics

---

## 🔧 Tech Stack

| Component | Tools |
|----------|------|
| Deep Learning | PyTorch, UNet, ResNet (feature extraction) |
| Computer Vision | OpenCV, Mediapipe (optional), Albumentations |
| Explainability | Grad-CAM |
| Backend (optional) | Streamlit / FastAPI |
| Language | Python |

---

## 📦 Repository Structure

📁 src # Core training and inference code
📁 segmentation # UNet model + masks
📁 classification # CNN model + feature extraction
📁 data_samples # Sample test images
📁 results # Metrics + logs (no visualizations required)
📄 train_segmentation.py
📄 train_classifier.py
📄 inference.py
📄 requirements.txt
📄 README.md
Performance Summary
Task	Metric	Score
Segmentation	IoU	89%
Classification	Accuracy	87%
Explainability	Visual mapping reliability	High
✅ Target Applications
Early autism screening assistance

Healthcare-tech research

Explainable medical AI systems

Clinical decision support tools


