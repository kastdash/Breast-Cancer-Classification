# 🩺 Breast Cancer Classification Using Machine Learning

This project uses the **Breast Cancer Wisconsin dataset** from `scikit-learn` to build and evaluate machine learning models that classify tumors as **malignant** or **benign** based on diagnostic features.

---

## 📊 Project Overview
The goal of this project is to:
- Load and explore the breast cancer dataset.
- Preprocess and scale the data.
- Train classification models.
- Evaluate model performance using accuracy and other metrics.

---

## ⚙️ Tools & Libraries
- Python 3
- NumPy
- Pandas
- Matplotlib
- scikit-learn

---

## 🧠 Models Implemented
- Logistic Regression  
- Random Forest Classifier  
- Support Vector Machine (SVM)  

Each model was trained on the preprocessed data and evaluated using:
- Accuracy score  
- Confusion matrix  
- Classification report (precision, recall, F1-score)

---

## 📈 Results
- The models achieved high accuracy (>90%) on the test dataset.
- Logistic Regression and Random Forest performed comparably well.
- The features **worst radius**, **mean texture**, and **mean area** showed high importance in classification.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/kastdash/BreastCancerClassification.git
   cd BreastCancerClassification
