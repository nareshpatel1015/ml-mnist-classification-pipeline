# 🧠 MNIST Classification Pipeline

An end-to-end implementation of digit classification on the MNIST dataset, inspired by Chapter 3 *“Classification”* from **Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow (2nd Edition)** by Aurélien Géron.

This project demonstrates a practical ML workflow using Scikit-Learn — from data exploration to model evaluation — implemented on Google Colab.

---

## 🚀 Overview

The notebook and script cover:
- Binary classification (`5` vs. not `5`)  
- Multiclass classification (digits `0–9`)  
- Model evaluation with precision, recall, F1-score, and confusion matrices  
- Cross-validation and feature scaling

---

## 📊 Results Summary

**Binary Classification (SGDClassifier)**  
- Accuracy: **0.968**  
- Precision: **0.698**, Recall: **0.841**, F1: **0.763**

**Multiclass Classification**
- SGD (scaled) CV scores: `[0.906, 0.896, 0.902]`  
- KNN F1 Score: **0.978**  
- SVC Decision Scores (digit 5): `[1.72, 2.73, 7.26, 8.30, -0.31, 9.31, 1.71, 2.78, 6.19, 4.86]`

---

## ⚙️ Tech Stack
- **Python**, **Scikit-Learn**, **NumPy**, **Matplotlib**  
- Executed on **Google Colab**  
- Dataset: **MNIST Handwritten Digits**

---


---

## 🔍 Key Takeaways
- Feature scaling improves SGD performance  
- Confusion matrices clarify misclassifications  
- KNN yields top accuracy with higher computational cost  

---

## 👨‍💻 Developer
**Naresh Patel**  
[GitHub](https://github.com/nareshpatel1015) • [LinkedIn](https://www.linkedin.com/in/naresh-patel-2019

---

## 📘 Reference
*Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow (2nd Edition)* – Aurélien Géron

