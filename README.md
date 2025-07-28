# 🧠 Alzheimer's Disease Detection

## 📌 Project Overview

This project builds and compares two machine learning models to predict whether a patient has Alzheimer's disease. By analyzing patient health data, the goal is to assist in early diagnosis, potentially improving outcomes through timely intervention.

---

## 📂 Dataset

- **Source**: [Kaggle](https://www.kaggle.com)
- **Size**: 2,149 patient records (ID range: 4751 to 6900)
- **Features**:
  - Demographics
  - Lifestyle factors
  - Medical history
  - Clinical measurements
  - Cognitive and functional assessments
  - Symptoms
  - Diagnosis labels

---

## 🛠️ Feature Engineering

The following preprocessing steps were performed:

- ✅ Feature selection
- 🧼 Handling missing and duplicated values
- 🔠 Encoding categorical variables
- 📊 Normalizing and scaling data

---

## 🤖 Models Used

### 1. k-Nearest Neighbors (KNN)

- 📌 Best **K value** selected using **F1-Score**
- 🔍 Higher F1-Score (closer to 1) indicates better performance

### 2. Random Forest Classifier

- 🌲 Best **n_estimators** (number of trees) chosen using **Accuracy Score**
- 🏆 Best result: **100 trees**, reaching ~70% accuracy

---

## 📊 Model Comparison

Both models were evaluated using:

- **F1-Score**
- **Accuracy Score**

Each model showed different strengths. Further hyperparameter tuning and feature analysis could enhance real-world effectiveness.

---

## 👨‍💻 Author

**Omar Al Zoghbi**

## 👨‍🏫 Instructor

**Ali Sabra**
