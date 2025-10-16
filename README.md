# 🩺 Breast Cancer Classification Using Machine Learning

This project investigates the role of machine learning in healthcare innovation, specifically in improving cancer diagnostics. Predictive modeling of breast cancer data in this analysis demonstrates how computational approaches may complement medical expertise and contribute to better patient outcomes in real-world healthcare environments.
This project implements and compares multiple machine learning algorithms to classify tumors as **malignant** or **benign** using the **Breast Cancer Wisconsin dataset** from `scikit-learn`.  
The models are evaluated through **10-fold cross-validation** to determine their mean accuracy and robustness.

---

## 📊 Project Overview

The primary objective of this project is to identify which machine learning model performs best for breast cancer diagnosis using diagnostic features from cell nuclei.  
Each model is trained and evaluated on the same dataset to ensure a fair comparison.

The workflow includes:
1. Loading and exploring the dataset  
2. Implementing multiple classification algorithms  
3. Performing 10-fold cross-validation for model comparison  
4. Printing mean accuracy and standard deviation for each model  

---

## ⚙️ Tools & Libraries

- **Python 3**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Scikit-learn**

---

## 🧠 Models Implemented

The following classification models were trained and evaluated:

| Model | Description |
|--------|--------------|
| **K-Nearest Neighbors (KNN)** | Classifies a sample based on the majority label of its nearest neighbors. |
| **Support Vector Machine (SVM)** | Finds an optimal boundary separating benign and malignant cases. |
| **Gaussian Naive Bayes (GNB)** | Uses probabilistic assumptions for quick classification. |
| **Random Forest Classifier** | Ensemble of decision trees that improves prediction stability and accuracy. |
| **Multi-Layer Perceptron (MLP)** | A simple feed-forward neural network for nonlinear decision boundaries. |

Each model was evaluated using **10-fold cross-validation**, and results were reported as **mean accuracy (%)** and **standard deviation** across folds.

---

## 📈 Results Summary

- All models achieved **high accuracy (above 90%)** on average.  
- **Random Forest** and **SVM** generally provided the **best performance** with the lowest variability.  
- **GaussianNB** was the fastest but slightly less accurate.  
- **MLPClassifier** achieved competitive accuracy but required more computational time.

---

## 🏁 Conclusion

This analysis demonstrates that classical machine learning models can effectively classify breast cancer cases based on cell feature data.  
Among the models tested, **Random Forest** and **SVM** offered the best balance between accuracy and reliability.

### 🔮 Future Improvements
- Perform **hyperparameter tuning** (e.g., with `GridSearchCV`).  
- Visualize **feature importance** and **decision boundaries**.  
- Experiment with **deep learning architectures** (e.g., small neural networks).  

---

## 🚀 How to Run

1. **Clone this repository:**
   ```bash
   git clone https://github.com/kastdash/BreastCancerClassification.git
   cd BreastCancerClassification

