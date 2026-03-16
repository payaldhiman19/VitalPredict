# 🏥 VitalPredict  - Disease Prediction System

A machine learning-based disease prediction system that diagnoses diseases based on input symptoms using multiple classification algorithms.

## 🎯 Overview

**VitalPredict Model 2** is an advanced disease prediction system that leverages machine learning to predict diseases based on patient symptoms. The system uses multiple classification algorithms to ensure accurate and reliable diagnoses.

### Key Highlights:
- 🤖 **6 Classification Algorithms** for robust predictions
- 📊 **97.62% Accuracy** achieved with KNN classifier
- 🎨 **Cross-validation** for model reliability
- ⚡ **Real-time Predictions** with symptom inputs
- 📈 **Comprehensive Evaluation Metrics** (Accuracy, Precision, Recall, F1-Score)

---

## ✨ Features

### Core Features:
✅ **Multiple Classification Models**
   - Logistic Regression
   - Random Forest Classifier
   - K-Nearest Neighbors (KNN)
   - Naive Bayes
   - Support Vector Machine (SVM)
   - Gradient Boosting

✅ **Comprehensive Data Preprocessing**
   - StandardScaler for feature normalization
   - LabelEncoder for categorical encoding
   - Data cleaning and validation

✅ **Advanced Model Evaluation**
   - Accuracy, Precision, Recall metrics
   - F1-Score calculation
   - Confusion Matrix analysis

✅ **User-Friendly Prediction Interface**
   - Symptom-based disease diagnosis
   - Input validation and error handling
   - Clear prediction output with confidence

✅ **Visualization & Analytics**
   - Performance comparison charts
   - Model accuracy bar plots
   - Classification reports

---

## 📊 Dataset

### Data Source:
- **Training Dataset:** `Training.csv` (Used for model training)
- **Testing Dataset:** `Testing.csv` (Used for model evaluation)

### Dataset Characteristics:
- **Features:** 132 symptom columns (binary: 0 or 1)
- **Target:** Disease/Prognosis (categorical)
- **Total Classes:** 41 different diseases

### Data Preprocessing Steps:
1. Removal of unnamed columns
2. Feature-target separation
3. Label encoding for diseases
4. StandardScaler normalization
5. Data shuffling for randomness

---


## 📈 Results

### Model Performance Comparison:

| Classifier | Accuracy | Precision | Recall | F1 Score |
|-----------|----------|-----------|--------|----------|
| **KNN** | **97.62%** | **98.78%** | **98.78%** | **98.37%** |
| Logistic Regression | 95.24% | 95.12% | 96.34% | 95.12% |
| Random Forest | 80.95% | 77.24% | 81.71% | 77.93% |
| Naive Bayes | 59.52% | 57.06% | 60.98% | 57.60% |


### Key Insights:
📌 **KNN** achieved the highest accuracy (97.62%)
📌 **Logistic Regression** provides strong baseline (95.24%)
📌 **Ensemble methods** show promising potential for further optimization
📌 **Model ensemble** could improve robustness further

---
