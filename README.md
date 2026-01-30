# 🧠 Handwritten Digit Classification using KNN

## 📌 Task Overview
This project is part of the **AI & ML Internship – Task 10**, focused on implementing the **K-Nearest Neighbors (KNN)** algorithm for handwritten digit classification.  
The goal is to understand **distance-based classification**, the importance of **feature scaling**, and how to **tune K values** for better performance.

---

## 🗂 Dataset Used
**Sklearn Digits Dataset**

- Loaded using `load_digits()` from `sklearn.datasets`
- Contains **1,797 grayscale images**
- Image size: **8 × 8 pixels**
- Total classes: **10 (digits 0–9)**
- Each image is flattened into **64 numerical features**

This dataset is built into Scikit-learn, so no external download is required.

---

## 🛠 Tools & Libraries
- Python  
- Scikit-learn  
- Matplotlib  
- NumPy  

---

## 🔍 Steps Performed
1. Loaded the digits dataset and verified data shape
2. Visualized sample digit images with labels
3. Split data into training and testing sets
4. Applied **StandardScaler** for feature normalization
5. Trained KNN model with different K values (3, 5, 7, 9)
6. Evaluated accuracy for each K
7. Plotted **Accuracy vs K** graph
8. Selected the best K based on accuracy
9. Generated **Confusion Matrix**
10. Displayed test images with predicted labels

---

## 📊 Results
- Achieved high accuracy in handwritten digit classification
- Best K value selected using validation accuracy
- Confusion matrix shows strong classification performance with minimal misclassification

---

## 📈 Visual Outputs
- ✔ Accuracy vs K graph  
- ✔ Confusion Matrix  
- ✔ Sample digit predictions  


## 📁 Project Structure
