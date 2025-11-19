# Breast Cancer Classification (UCI Dataset)

A machine learning project for classifying breast cancer tumors as **benign** or **malignant** using the **UCI Breast Cancer Wisconsin Dataset**.  
The project compares multiple models including Logistic Regression, SVM, Random Forest, and XGBoost, with detailed evaluation metrics and feature importance analysis.

---

## Dataset
The dataset is loaded directly from `sklearn`:

- **569 samples**
- **30 numerical features**
- **Target classes:**  
  - 0 → Malignant  
  - 1 → Benign  

---

## Models Implemented
The following ML models are trained and evaluated:

- **Logistic Regression**
- **SVM (RBF Kernel)**
- **Random Forest Classifier**
- **XGBoost Classifier**

All features are standardized using `StandardScaler`.

---

## Evaluation Metrics
For each model, the script prints:

- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report** (precision, recall, F1-score)

# Model Performance Summary — Breast Cancer Classification (UCI Dataset)

This summary compares four machine-learning models: **Logistic Regression**, **SVM (RBF)**, **Random Forest**, and **XGBoost**.  
All models achieved strong results, with accuracies ranging from **96% to 98%**.

---
## 1. Logistic Regression
- **Accuracy:** `0.9825`
- **Confusion Matrix:**
  - TN: 41 | FP: 1  
  - FN: 1 | TP: 71
- **Highlights:**  
  - Excellent precision, recall, and F1-score  
  - Strong linear baseline model  
  - Zero major misclassifications

---

## 2. SVM (RBF Kernel)
- **Accuracy:** `0.9825`
- **Confusion Matrix:**  
  - Identical to Logistic Regression
- **Highlights:**  
  - Performs just as well as Logistic Regression  
  - Handles non-linear data effectively  
  - Very stable, high-performance classifier  

---

## 3. Random Forest
- **Accuracy:** `0.9649`
- **Confusion Matrix:**
  - TN: 39 | FP: 3  
  - FN: 1 | TP: 71
- **Highlights:**  
  - Slightly lower accuracy due to more false positives  
  - Very strong recall for malignant cases  
  - Provides feature importance insights  

---

## 4. XGBoost
- **Accuracy:** `0.9649`
- **Confusion Matrix:**  
  - TN: 41 | FP: 1  
  - FN: 3 | TP: 69
- **Highlights:**  
  - Good accuracy  
  - Slightly higher false negatives  
  - Performs well with minimal tuning  

---

# Overall Comparison

| Model               | Accuracy | Summary |
|---------------------|----------|---------|
| **Logistic Regression** |  **0.9825** | Best performance, simplest model |
| **SVM (RBF)**           |  **0.9825** | Best performance, excellent non-linear capability |
| Random Forest           | 0.9649 | Good generalization, interpretable |
| XGBoost                 | 0.9649 | Strong, but slightly more false negatives |

---

# Best Models  
**Logistic Regression** and **SVM (RBF)** achieved the best overall results with identical accuracy and balanced classification performance.

---
##  Author

M. M. Arif Bakhtiar
mmarifbakhtiar.ece.ruet@gmail.com


