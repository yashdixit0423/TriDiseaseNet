
# 🔬 TriDiseaseNet – Retinal Disease Classification

A deep learning-based retinal disease classification system built using **PyTorch** and **CNN architectures**, trained on the ODIR (Ocular Disease Intelligent Recognition) dataset.

---

## 📌 Overview

This project focuses on detecting multiple retinal diseases from fundus images using a **multi-label classification approach**.  
The model learns to identify different eye conditions from retinal scans.

---

## 🧠 Model Architecture

- Custom CNN-based architecture  
- Multi-label classification setup  
- Sigmoid activation for independent class prediction  

---

## 📂 Dataset

- **ODIR (Ocular Disease Intelligent Recognition) Dataset**
- Retinal fundus images with multiple disease labels  

### Disease Labels:
- Normal (N)  
- Diabetes (D)  
- Glaucoma (G)  
- Cataract (C)  
- Age-related Macular Degeneration (A)  
- Hypertension (H)  
- Pathological Myopia (M)  
- Other Diseases (O)  

---

## ⚙️ Pipeline

### Data Processing
- Image-label mapping using dataset annotations  
- Multi-label encoding  
- Train-test split  

### Transformations
- Resize (224 × 224)  
- Normalization  
- Data augmentation (flip, rotation)  

---

## 🚀 Training Details

- Loss Function: Binary Cross Entropy (BCEWithLogitsLoss)  
- Optimizer: Adam  
- Multi-label classification strategy  

---

## 📊 Evaluation Results

### Overall Performance
- **Test Accuracy:** ~85%  
- **F1-Score (Macro):** ~0.78  

### Key Observations
- Strong performance on dominant conditions (Normal, Diabetes)  
- Slightly lower performance on rare diseases (e.g., AMD, Myopia)  
- Multi-label setup makes the task more challenging than single-label classification  

---

## ✨ Key Highlights

- Multi-label disease prediction from retinal images  
- End-to-end deep learning pipeline  
- Handles real-world medical complexity (multiple conditions per image)  
- Designed for extension into full diagnostic system  

---

## 🔮 Future Scope

- Improve performance using pretrained models (ResNet, EfficientNet)  
- Apply class balancing techniques  
- Combine with skin model for full TriDiseaseNet system  
- Deploy as a healthcare AI assistant  

---
