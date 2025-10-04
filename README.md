# 🌸 Iris Flowers Classification

This project demonstrates the use of **machine learning techniques** to classify iris flowers into three species: **Setosa, Versicolor, and Virginica**, using the well-known **Iris dataset**.

---

## 📌 Project Overview
The Iris dataset is one of the most famous datasets in machine learning. It contains 150 samples with 4 features:
- Sepal length  
- Sepal width  
- Petal length  
- Petal width  

The goal is to predict the species of an iris flower based on these features.

---

## 📊 Data Source
The dataset is publicly available from the **UCI Machine Learning Repository**:  
[https://archive.ics.uci.edu/ml/datasets/iris](https://archive.ics.uci.edu/ml/datasets/iris)  

It is also included with **Scikit-learn** for easy loading:
```python
from sklearn.datasets import load_iris
iris = load_iris()
