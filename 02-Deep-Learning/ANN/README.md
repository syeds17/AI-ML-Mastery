# 🧠 Car Purchase Amount Prediction using Artificial Neural Networks (ANN)

## 📌 Project Overview

This project demonstrates the implementation of an **Artificial Neural Network (ANN)** using **TensorFlow and Keras** to predict the **Car Purchase Amount** of customers based on their financial and demographic information.

The project covers the complete Deep Learning workflow, including data preprocessing, feature scaling, model building, training, evaluation, prediction, and model saving.

---

## 🎯 Objective

The objective of this project is to:

- Understand the fundamentals of Artificial Neural Networks.
- Build a Deep Learning regression model.
- Predict car purchase amounts using customer data.
- Learn the complete ANN workflow using TensorFlow and Keras.

---

## 📊 Dataset Features

Input Features:

- Gender
- Age
- Annual Salary
- Credit Card Debt
- Net Worth

Target Feature:

- Car Purchase Amount

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- TensorFlow
- Keras
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Project Workflow

1. Import required libraries
2. Load the dataset
3. Perform Exploratory Data Analysis (EDA)
4. Remove unnecessary features
5. Split features and target
6. Apply MinMax Scaling
7. Train-Test Split
8. Build the ANN model
9. Compile the model
10. Train the model
11. Evaluate the model
12. Predict car purchase amount
13. Save the trained model

---

## 🧠 ANN Architecture

Input Layer

↓

Hidden Layer (ReLU)

↓

Hidden Layer (ReLU)

↓

Output Layer (Linear)

---

## ⚙️ Model Configuration

| Parameter | Value |
|-----------|-------|
| Optimizer | Adam |
| Loss Function | Mean Squared Error (MSE) |
| Epochs | *(Your Value)* |
| Batch Size | *(Your Value)* |

---

## 📈 Model Evaluation

The trained ANN model was evaluated using:

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score
- Training Loss Curve

The model successfully learned the relationship between customer attributes and the target variable.

---

## 📁 Project Structure

```text
ANN/
│
├── ANN.ipynb
├── README.md
├── Data/
│   └── Car_Purchasing_Data.csv
├── assets/
├── outputs/
└── model/
```

---

## 📚 Key Learnings

- Understanding Artificial Neural Networks
- Data preprocessing for Deep Learning
- Feature Scaling using MinMaxScaler
- Building Sequential models
- Dense Layers
- Activation Functions
- Model Training
- Model Prediction
- Regression using ANN
- TensorFlow & Keras

---

## 🚀 Future Improvements

Possible improvements include:

- Hyperparameter tuning
- Experimenting with different activation functions
- Adding Dropout layers to reduce overfitting
- Comparing ANN performance with traditional Machine Learning models
- Deploying the trained model using Streamlit or Flask

---

## 👨‍💻 Author

**Syed Sadath**

AI & ML Enthusiast | Python | Machine Learning | Deep Learning

---

⭐ This project is part of my **AI-ML-Mastery** repository, where I document my learning journey by implementing Machine Learning, Deep Learning, and Computer Vision concepts through hands-on projects.