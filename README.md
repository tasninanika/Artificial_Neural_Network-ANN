# 🧠 Customer Churn Prediction using ANN

A deep learning based project to predict **customer churn** using an **Artificial Neural Network (ANN)**. The model is trained on the **Churn\_Modelling.csv** dataset.

---

## 📌 Project Overview

Customer churn is when customers stop using a company's services. Predicting churn helps businesses take proactive steps to improve retention.

This project uses an **ANN built with TensorFlow/Keras** to classify whether a customer will churn or not.

---

## 📂 Dataset

* **File:** `Churn_Modelling.csv`
* **Rows:** 10,000
* **Features:** Customer demographics, account information, and activity details
* **Target:** `Exited` (1 = Customer Churned, 0 = Customer Retained)

---

## ⚙️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![NumPy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge\&logo=plotly\&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge\&logo=scikit-learn\&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge\&logo=tensorflow\&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge\&logo=keras\&logoColor=white)

---

## 🛠️ Project Workflow

### 🔹 Data Preprocessing

* Handled missing values
* Encoded categorical features (**Gender, Geography**)
* Feature scaling using **StandardScaler**

### 🔹 Model Building

* **Input layer:** Features
* **Hidden layers:** Dense + ReLU activation
* **Output layer:** Sigmoid activation

### 🔹 Model Training

* **Optimizer:** Adam
* **Loss Function:** Binary Crossentropy
* **Metrics:** Accuracy

### 🔹 Evaluation

* Confusion Matrix
* Accuracy, Precision, Recall, F1-score
