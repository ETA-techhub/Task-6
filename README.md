# 🌸 Task 6 – K-Nearest Neighbors (KNN) Classification

This project is part of my AI & ML Internship and focuses on understanding and implementing the **K-Nearest Neighbors (KNN)** algorithm using the **Iris Dataset**. The task involves training a KNN classifier, evaluating it, and visualizing decision boundaries.

---

## 🎯 Objective

- Implement the KNN algorithm for classification.
- Explore how different values of **K** affect model performance.
- Visualize the model's decision-making.
- Understand instance-based learning and distance metrics.

---

## 📊 Dataset Used

**Iris Dataset** from Scikit-learn:
- 150 samples of iris flowers
- 3 classes: *Setosa*, *Versicolor*, *Virginica*
- 4 features: Sepal length, Sepal width, Petal length, Petal width

---

## 🛠 Tools & Libraries

- Python
- Scikit-learn
- Matplotlib
- Numpy

---

## 📌 Steps Performed

1. Loaded the Iris dataset using `sklearn.datasets`.
2. Normalized features using `StandardScaler` to ensure fair distance calculations.
3. Split the dataset into training and testing sets using `train_test_split`.
4. Trained a **KNeighborsClassifier** model with different values of K (1, 3, 5, 7, 9).
5. Evaluated accuracy, confusion matrix, and classification report for each K.
6. Plotted **accuracy vs K** graph.
7. (Bonus) Visualized **decision boundaries** using the first 2 features.

---

## 📈 Output Highlights

- Best accuracy observed around **K=5**.
- Decision boundaries clearly separate the classes with normalized features.
- Normalization and proper K selection significantly affect model performance.

---

## 🧠 Key Learnings

- KNN is a **distance-based** classifier that doesn't learn parameters but compares inputs.
- Normalization is critical since KNN relies on **Euclidean distance**.
- Choosing the right value of K is a balance between underfitting and overfitting.

---

