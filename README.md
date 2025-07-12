# 💼 Customer Churn Prediction using Deep Learning (ANN)

<p align="center">
  <img src="https://img.icons8.com/fluency/96/artificial-intelligence.png" width="80"/>
</p>

> A Deep Learning-based solution to predict customer churn using Artificial Neural Networks (ANN) and Streamlit-powered interactive dashboard.

---

## 🧠 Project Overview

Customer churn is a major concern for businesses. This project predicts whether a customer will **leave (churn)** or **stay**, using a neural network built with **TensorFlow**.

---

## 🚀 Tech Stack

| Tool / Library       | Description                               |
|----------------------|-------------------------------------------|
| `TensorFlow==2.15.0` | Core deep learning framework (ANN model)  |
| `Pandas`             | Data handling and preprocessing           |
| `NumPy`              | Numerical operations                      |
| `Scikit-Learn`       | Model selection, preprocessing tools      |
| `Matplotlib`         | Visualization                             |
| `Streamlit`          | Web app for interactive model inference   |
| `TensorBoard`        | Model training visualization              |
| `SciKeras`           | TensorFlow + Scikit-learn bridge          |

---

## 📊 Dataset Features

| Feature              | Description                             |
|----------------------|-----------------------------------------|
| `Geography`          | Country of the customer                 |
| `Gender`             | Male / Female                           |
| `Age`                | Age of customer                         |
| `Balance`            | Account balance                         |
| `CreditScore`        | Customer's credit score                 |
| `EstimatedSalary`    | Salary estimation                       |
| `Tenure`             | Years with the company                  |
| `NumOfProducts`      | Products used by the customer           |
| `HasCrCard`          | 1 = Has Credit Card, 0 = No             |
| `IsActiveMember`     | 1 = Active, 0 = Inactive                |
| `Exited`             | **Target Variable** (1 = Churned, 0 = Stayed) |

---

## 🧪 Model Summary

- Model Type: **Artificial Neural Network (ANN)**
- Layers: Dense → ReLU + Dropout → Dense → Sigmoid
- Loss Function: `binary_crossentropy`
- Optimizer: `Adam`
- Accuracy Achieved: ⭐ ~85-90% (varies by tuning)
- Training Visualization: Enabled with **TensorBoard**

---


### 🔍 Streamlit UI
<p align="center">
  <img src="https://github.com/priyanshu-sen-07/Churn-Prediction-using-ANN/blob/main/Screenshot%202025-07-12%20220019.png" width="80%" alt="Streamlit App UI"/>
</p>



