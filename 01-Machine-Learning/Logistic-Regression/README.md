# 🩺 Diabetes Prediction using Logistic Regression

## 📌 Project Overview

This project demonstrates the implementation of a **Logistic Regression** model to predict whether a patient is likely to have diabetes based on various medical attributes. The project covers the complete machine learning workflow, including data exploration, preprocessing, feature scaling, model training, evaluation, and prediction.

---

## 🎯 Objective

To build a binary classification model that predicts whether a patient has diabetes (`Outcome = 1`) or not (`Outcome = 0`) using Logistic Regression.

---

## 📂 Dataset Information

The dataset contains the following features:

| Feature | Description |
|---------|-------------|
| Pregnancies | Number of pregnancies |
| Glucose | Blood glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skin fold thickness (mm) |
| Insulin | 2-Hour serum insulin (mu U/ml) |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function (family history score) |
| Age | Age of the patient |
| Outcome | Target Variable (0 = Non-Diabetic, 1 = Diabetic) |

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
4. Check dataset information and missing values
5. Select features and target variable
6. Split the dataset into training and testing sets
7. Apply feature scaling using **StandardScaler**
8. Train the Logistic Regression model
9. Evaluate model performance
10. Predict diabetes status for new patient data

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Dataset overview (`head()`)
- Dataset information (`info()`)
- Statistical summary (`describe()`)
- Missing value analysis
- Correlation Heatmap

### Key Observations

- The dataset contains only numerical features.
- Feature scaling is required because the feature values are on different scales.
- The target variable is binary:
  - **0 → Non-Diabetic**
  - **1 → Diabetic**

---

## 🤖 Model Used

**Algorithm**

- Logistic Regression

---

## 📈 Model Evaluation

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

### Results

| Metric | Value |
|---------|--------|
| Accuracy | **75.32%** |

The Logistic Regression model achieved an accuracy of approximately **75%**, demonstrating good performance in classifying diabetic and non-diabetic patients on this dataset.

---

## 🔮 Sample Prediction

The trained model can predict whether a patient is diabetic based on the following medical information:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

Output:

- **0 → Non-Diabetic**
- **1 → Diabetic**

---

## 📁 Project Structure

```
Logistic-Regression/
│
├── Logistic_Regression.ipynb
├── diabetes_data.csv
├── README.md
├── requirements.txt
├── .gitignore
├── assets/
└── outputs/
```

---

## 📚 Key Learnings

Through this project, I gained practical experience in:

- Binary Classification
- Logistic Regression
- Exploratory Data Analysis (EDA)
- Feature Scaling using StandardScaler
- Train-Test Split
- Model Training
- Model Evaluation
- Confusion Matrix Interpretation
- Classification Report Analysis
- Predicting outcomes for new patient data

---

## 🚀 Future Improvements

- Handle missing or invalid values more effectively.
- Perform hyperparameter tuning.
- Apply Cross Validation for more reliable evaluation.
- Compare Logistic Regression with Decision Tree, Random Forest, and Support Vector Machine.
- Deploy the trained model using Streamlit or Flask.

---

## 👨‍💻 Author

**Syed Sadath**

AI & ML Enthusiast | Python | Machine Learning | Data Science

---

⭐ If you found this project useful, feel free to explore the repository and share your feedback.