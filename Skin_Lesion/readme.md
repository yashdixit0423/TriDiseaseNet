# 🔥 TriDiseaseNet – Skin Disease Classification

A deep learning-based skin disease classification system built using **PyTorch** and **ResNet-18**, trained on the HAM10000 dataset.

---

## 📌 Overview

This project focuses on classifying dermoscopic images into multiple skin disease categories using a **transfer learning approach**.  
A pretrained ResNet-18 model is fine-tuned to perform **7-class classification**.

---

## 🧠 Model Architecture

- Base Model: ResNet-18  
- Transfer Learning applied  
- Final Fully Connected layer modified → 7 output classes  

---

## 📂 Dataset

- **HAM10000 Dataset**
- Total Samples: **10,015 images**

### Classes:
- akiec  
- bcc  
- bkl  
- df  
- mel  
- nv  
- vasc  

---

## ⚙️ Pipeline

### Data Processing
- Label encoding for categorical labels  
- Image path mapping from multiple directories  
- Stratified train-test split  

### Transformations
- Resize (224 × 224)  
- Random Horizontal Flip  
- Random Rotation  
- Color Jitter  
- Normalization  

---

## 🚀 Training Details

- Optimizer: Adam  
- Loss Function: CrossEntropyLoss  
- Epochs: 5  

### Training Performance (Final Epoch)
- Train Accuracy: **89.85%**  
- Validation Accuracy: **83.67%**  

---

## 📊 Evaluation Results

### Overall Performance
- **Test Accuracy:** 83.67%  
- **Test Loss:** 0.4752  

### Detailed Classification Report

| Class | Precision | Recall | F1-Score |
|------|----------|--------|---------|
| akiec | 0.96 | 0.38 | 0.55 |
| bcc   | 0.70 | 0.83 | 0.76 |
| bkl   | 0.70 | 0.76 | 0.73 |
| df    | 0.79 | 0.65 | 0.71 |
| mel   | 0.56 | 0.63 | 0.59 |
| nv    | 0.92 | 0.91 | 0.92 |
| vasc  | 0.95 | 0.75 | 0.84 |

### Averages
- **Macro Avg F1-score:** 0.73  
- **Weighted Avg F1-score:** 0.84  

---

## ✨ Key Highlights

- Achieved **~84% test accuracy** on a real-world medical dataset  
- Strong performance on dominant classes (e.g., *nv: 0.92 F1-score*)  
- End-to-end PyTorch pipeline from preprocessing to evaluation  
- Scalable architecture for multi-disease expansion  

---

## 🔮 Future Scope

- Improve minority class performance (akiec, df)  
- Apply class balancing / weighted loss  
- Extend to retinal disease classification  
- Deploy as an AI-powered diagnostic tool  

---
