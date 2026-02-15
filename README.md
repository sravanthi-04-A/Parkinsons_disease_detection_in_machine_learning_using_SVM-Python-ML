# 🧠 Parkinson’s Disease Detection Using SVM

## 📌 Overview

This project focuses on detecting Parkinson’s Disease using a supervised machine learning approach.  
A Support Vector Machine (SVM) classifier is trained on biomedical voice measurement data to predict whether a patient has Parkinson’s Disease.

The objective is to build a reliable, non-invasive early detection model using structured data analysis and classification techniques.

---

## 🎯 Problem Statement

Parkinson’s Disease is a progressive neurological disorder that affects movement and speech patterns. Early detection plays an important role in improving treatment outcomes.

This project aims to:

- Perform data preprocessing and feature analysis  
- Train and optimize an SVM model  
- Evaluate classification performance  
- Visualize prediction results using evaluation metrics  

---

## 🗂 Dataset Information

- The dataset consists of biomedical voice measurements.
- Each row represents an individual patient.
- Features include frequency measures, vocal jitter, shimmer, and other speech-related attributes.
- The target variable indicates:
  - `1` → Parkinson’s Disease present  
  - `0` → Healthy  

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook  

---

## 🔍 Machine Learning Workflow

### 1️⃣ Data Preprocessing
- Checked and handled missing values  
- Performed feature scaling  
- Split dataset into training and testing sets  

### 2️⃣ Model Development
- Implemented Support Vector Machine (SVM)
- Used RBF (Radial Basis Function) kernel
- Applied hyperparameter tuning to improve performance

### 3️⃣ Model Evaluation
- Accuracy Score  
- Confusion Matrix  
- Precision & Recall  
- Performance visualization  

---

## 📊 Results

- Achieved **92% accuracy**
- Model performance validated using confusion matrix
- Demonstrated effective classification of Parkinson’s vs Healthy cases

---

## 📈 Confusion Matrix

Below is the confusion matrix generated from the test dataset:

![Confusion Matrix](confusion_matrix.png)

---

## 🚀 How to Run This Project

### Step 1: Clone the repository

```bash
git clone https://github.com/your-username/your-repository-name.git
