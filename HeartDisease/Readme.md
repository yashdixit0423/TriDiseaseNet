# ❤️ Cardiovascular Disease Prediction

## 📌 Overview
This project implements a machine learning pipeline to predict cardiovascular disease using patient health data.  
It includes data preprocessing, feature engineering, training multiple models, and evaluating their performance using standard metrics and visualizations.

---

## 🤖 Models Used
- Random Forest  
- XGBoost  
- LightGBM  
- Decision Tree  
- K-Nearest Neighbors (KNN)  
- Logistic Regression  

---

## 📁 Directory Structure
------------------
project_Foxtrot/
├── src/
│   ├── predict.ipynb                - Jupyter notebook with the main code
│   ├── cardio_train.csv             - Dataset file
|   |── testingsavelmodels.ipynb     - Testing the saved models with sample inputs   
├── models/
│   ├── RandomForest_model.pkl      - Trained Random Forest model
│   ├── XGBoost_model.pkl           - Trained XGBoost model
│   ├── LightGBM_model.pkl          - Trained LightGBM model
│   ├── DecisionTree_model.pkl      - Trained Decision Tree model
│   ├── KNN_model.pkl               - Trained KNN model
│   ├── LogisticRegression_model.pkl - Trained Logistic Regression model
│   ├── scaler.pkl                  - StandardScaler object
├── outputs/
│   ├── correlation_matrix.png      - Correlation matrix plot
│   ├── confusion_matrix_*.png      - Confusion matrices for each model
│   ├── feature_importance_*.png    - Feature importance for Random Forest and XGBoost
│   ├── roc_curves.png              - ROC curves for all models
├── README.txt                      - This file has instructions 
├── requirements.txt                - Python dependencies


---

## 📂 Dataset
This project uses the **Cardiovascular Disease Dataset**.

### 📊 Details
- Source: Kaggle  
- Contains patient health records including:
  - Age  
  - Gender  
  - Height & Weight  
  - Blood Pressure  
  - Cholesterol  
  - Glucose Levels  
  - Lifestyle attributes (smoking, alcohol, activity)  

🔗 Dataset Link:  
https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset  

> ⚠️ Dataset is not included in the repository.

---

## ⚙️ Pipeline

### 🔹 Data Preprocessing
- Data cleaning and transformation  
- Feature scaling using StandardScaler  

### 🔹 Model Training
- Multiple models are trained and compared  

### 🔹 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

---

## 📊 Outputs

### 🧠 Models
- Saved `.pkl` files for each trained model  
- Scaler file for preprocessing  

### 📈 Visualizations
- Correlation Matrix  
- Confusion Matrices  
- Feature Importance plots  
- ROC Curves  

---

## 🚀 Running the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/project_Foxtrot.git
cd project_Foxtrot

