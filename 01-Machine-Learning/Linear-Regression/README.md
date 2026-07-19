# 📈 Medical Insurance Cost Prediction using Linear Regression

## 📌 Project Overview

This project demonstrates the implementation of a **Linear Regression** model to predict **medical insurance charges** based on customer information. The project covers the complete Machine Learning workflow, from data preprocessing and exploratory data analysis (EDA) to model training, evaluation, and prediction.

---

## 🎯 Objective

To build a Linear Regression model that predicts medical insurance charges using customer attributes such as age, sex, BMI, number of children, smoking status, and region.

---

## 📂 Dataset Information

The dataset contains the following features:

| Feature | Description |
|---------|-------------|
| Age | Age of the customer |
| Sex | Gender of the customer |
| BMI | Body Mass Index |
| Children | Number of dependent children |
| Smoker | Smoking status |
| Region | Residential region |
| Charges | Medical insurance charges (Target Variable) |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Project Workflow

1. Import required libraries
2. Load the dataset
3. Perform Exploratory Data Analysis (EDA)
4. Handle and encode categorical features
5. Select features and target variable
6. Split the dataset into training and testing sets
7. Train the Linear Regression model
8. Evaluate the model
9. Predict insurance charges for new customer data

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Dataset overview (`head()`)
- Dataset information (`info()`)
- Statistical summary (`describe()`)
- Missing value analysis
- Correlation Heatmap

### Key Observations

- Smoking status has the strongest influence on medical charges.
- Age has a moderate positive correlation with insurance charges.
- BMI also contributes to insurance cost.
- Sex, region, and number of children show relatively weaker linear relationships.

---

## 🤖 Model Used

**Algorithm**

- Multi-Linear Regression

---

## 📈 Model Evaluation

The model was evaluated using the following metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### Results

| Metric | Value |
|---------|--------|
| R² Score | **0.783** |
| MSE | **33,685,623.35** |

The model explains approximately **78% of the variance** in medical insurance charges, indicating good predictive performance for a baseline Linear Regression model.

---

## 🔮 Sample Prediction

The trained model can predict insurance charges for new customer data by providing values for:

- Age
- Sex
- BMI
- Number of Children
- Smoking Status
- Region

---

## 📁 Project Structure

```
Linear-Regression/
│
├── Linear_Regression.ipynb
├── insurance.csv
├── README.md
├── requirements.txt
├── .gitignore
├── assets/
│   ├── heatmap.png
│   └── actual_vs_predicted.png
└── outputs/
```

---

## 📚 Key Learnings

Through this project, I gained practical experience in:

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Categorical Feature Encoding
- Feature Selection
- Train-Test Split
- Building Regression Models
- Model Evaluation
- Making Predictions on New Data

---

## 🚀 Future Improvements

- Perform Feature Engineering to improve model performance.
- Compare Linear Regression with other regression algorithms.
- Apply Cross Validation for more reliable evaluation.
- Deploy the trained model as a web application using Streamlit or Flask.

---

## 👨‍💻 Author

**Syed Sadath**

AI & ML Enthusiast | Python | Machine Learning | Data Science

---

⭐ If you found this project useful, feel free to explore the repository and share your feedback.