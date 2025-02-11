# cancer_detection-
A machine learning project using Gradient Boosting to classify breast cancer cases based on medical features
# 🎯 Breast Cancer Classification using Gradient Boosting

🚀 **A machine learning project to classify breast cancer cases using Gradient Boosting.**  
This project evaluates multiple classification models and compares their performance using accuracy, precision, recall, and F1-score.

---

## 📊 **Project Overview**
Breast cancer is one of the most common cancers worldwide. This project uses **Gradient Boosting Classifier** to differentiate between **malignant and benign tumors** using machine learning techniques.

### **🔍 Models Used**
- **Gradient Boosting Classifier (Main Model)**
- Random Forest (Comparison Model)
- Support Vector Machine (SVM)

---

## 📂 **Dataset**
- Dataset: `Breast Cancer Wisconsin Dataset`
- Source: [Scikit-learn Breast Cancer Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)
- Features include **cell size, shape, mitosis count, chromatin texture, and other biological attributes**.

---

## 🔥 **Performance Metrics**
| Model | Accuracy | Precision | Recall | F1-Score |
|--------|---------|-----------|--------|----------|
| **Gradient Boosting** | 95.61% | 95.83% | 97.18% | 96.50% |
| Random Forest | 96.49% | 95.89% | 98.59% | 97.22% |
| SVM | 95.61% | 97.14% | 95.77% | 96.45% |

🔹 **Gradient Boosting performed well, balancing precision and recall effectively.**  
🔹 **Random Forest had the best recall, making it useful for identifying cancer cases.**  
🔹 **SVM had the highest precision, reducing false positives.**
