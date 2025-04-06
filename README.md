# 🍷 Wine Classification using PCA & Logistic Regression

This project demonstrates how to classify different types of wines using Machine Learning. We use **Logistic Regression** to build the model, and apply **Principal Component Analysis (PCA)** to reduce dimensions for better visualization and performance comparison.

---

## 📌 Problem Statement

Given a dataset with 13 chemical attributes of wines, predict the **wine class/type** using supervised machine learning.

---

## 📂 Dataset

- File: `Wine.csv`
- Total Samples: 178
- Features: 13 chemical properties (like alcohol, magnesium, flavanoids etc.)
- Target: 3 types of wine (Label: 0, 1, 2)

---

## 🔧 Technologies Used

- Python 🐍
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Logistic Regression
- PCA (Principal Component Analysis)

---

## 🧠 Project Workflow

### ✅ 1. Import Libraries  
All necessary libraries are imported (NumPy, pandas, sklearn, etc.)

### ✅ 2. Data Loading & Preprocessing  
- Load CSV using pandas  
- Split into features `X` and target `y`  
- Standardize the features using `StandardScaler`

### ✅ 3. Without PCA: Baseline Model  
- Train a **Logistic Regression** model on full 13 features  
- Predict on test set  
- Calculate accuracy and confusion matrix

### ✅ 4. With PCA: Dimensionality Reduction  
- Apply PCA to reduce 13 features down to 2 principal components  
- Train Logistic Regression again  
- Visualize the results using scatter plot  
- Compare accuracy and performance

---

## 📊 Comparison

| Approach        | Features Used | Accuracy | Visualization | Speed |
|----------------|---------------|----------|----------------|-------|
| Without PCA     | 13            | Higher   | ❌ Complex     | Slower |
| With PCA (2D)   | 2             | Slightly lower | ✅ Easy | Faster |

---

## 📈 Visualization

- 2D plots showing how Logistic Regression separates classes using PCA components.
- Color-coded graphs for easy understanding.

---

## 🔚 Conclusion

- PCA helps simplify data while preserving important patterns.
- Logistic Regression performs well on both versions.
- PCA is useful when you want fast processing or easy visualization.
- Original model (without PCA) is more accurate when full info is available.

---

## ✨ Author

**Sundram Tiwari**  
Aspiring Data Scientist | Machine Learning Enthusiast  
