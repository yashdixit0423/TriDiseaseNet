# 🧠 TriDiseaseNet – Multi-Disease Classification System

TriDiseaseNet is a deep learning-based system designed to classify multiple diseases across different medical domains using computer vision and machine learning techniques.

This repository contains **three independent disease classification modules**, each focusing on a specific medical domain.

---

## 📌 Overview

TriDiseaseNet aims to provide a unified framework for disease prediction using image-based and tabular data.  
Each module is built as a standalone pipeline while maintaining a consistent architecture for scalability and integration.

---

## 🧩 Modules Included

### 🧴 Skin Disease Classification
- Uses **HAM10000 dataset**
- Model: ResNet-18 (Transfer Learning)
- Task: Multi-class classification (7 classes)
- Achieves ~84% test accuracy  

---

### 👁️ Retinal Disease Classification
- Uses **ODIR dataset**
- Model: CNN / EfficientNet
- Task: Multi-label classification
- Handles multiple diseases per image  

---

### ❤️ Cardiovascular Disease Prediction
- Uses structured patient health data
- Models: Random Forest, XGBoost, LightGBM, etc.
- Task: Binary classification (disease vs no disease)

---


---

## ⚙️ Technologies Used

- Python  
- PyTorch  
- Scikit-learn  
- OpenCV  
- Pandas & NumPy  

---

## ✨ Key Highlights

- Multi-domain disease classification system  
- Combines **computer vision + tabular ML approaches**  
- Modular design (each disease as independent pipeline)  
- Scalable for future healthcare AI applications  

---

## 🔮 Future Scope

- Integrate all modules into a single unified interface  
- Deploy as a web application (Flask / FastAPI)  
- Add more disease domains  
- Improve model performance using advanced architectures  

---

## 🚀 Getting Started

Each module has its own setup and instructions.

👉 Navigate to respective folders:
- `skin/`
- `retina/`
- `cardiovascular/`

and follow their individual README files.

---


