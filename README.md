# 🩺 Diabetes Prediction using Machine Learning

A machine learning classification project designed to predict whether a patient is diabetic or non-diabetic based on key health indicators such as glucose level, BMI, age, and insulin level.

---

## 📌 Project Overview

This project applies supervised learning techniques to classify patients as diabetic or non-diabetic. The model aims to assist in **early diagnosis and risk assessment of diabetes** by analyzing critical health features. Multiple ML algorithms were trained and evaluated for optimal performance.

---

## 🚀 Key Features

- ✅ Built using Python and Scikit-learn
- 🔍 Predicts diabetes based on medical inputs
- ⚙️ Models used: **Logistic Regression**, **Random Forest**, **SVM**
- 🧼 Includes **data preprocessing**, **feature scaling**, and **model evaluation**
- 📊 Achieved **85% accuracy** with strong precision and recall scores

---

## 🧰 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---
In this project, our objective is to predict whether the patient has diabetes or not based on various features like *Glucose level, Insulin, Age, BMI*. We will perform all the steps from *Data gathering to Model deployment.* During Model evaluation, we compare various machine learning algorithms on the basis of accuracy_score metric and find the best one. Then we create a web app using Flask which is a python micro framework.




# **Screenshot**

![](screenshot.jpg)

# Installation

- Clone this repository and unzip it.

- After downloading, `cd` into the `flask` directory.

- Begin a new virtual environment with Python 3 and activate it.

- Install the required packages using 
   `pip install -r requirements.txt`

- Execute the command:
   `python app.py`


---

## 📊 Dataset Details

- Source: [PIMA Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- Features used:
  - Glucose
  - BMI
  - Age
  - Insulin
  - Blood Pressure
  - Skin Thickness
  - Diabetes Pedigree Function
  - Pregnancies
- Target: `Outcome` (0: Non-diabetic, 1: Diabetic)

---

## ⚙️ ML Pipeline

1. **Data Loading & Cleaning**
   - Handled missing values and outliers
2. **Feature Scaling**
   - Applied StandardScaler for normalization
3. **Model Training**
   - Logistic Regression
   - Random Forest Classifier
   - Support Vector Machine (SVM)
4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-Score
   - Confusion Matrix & ROC Curve

---

## 📈 Results

| Model              | Accuracy | Precision | Recall | F1-Score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | 82%      | 84%       | 80%    | 82%      |
| Random Forest       | 85%      | 86%       | 83%    | 84%      |
| SVM                 | 83%      | 85%       | 81%    | 83%      |

✅ **Best Accuracy:** 85% (Random Forest)  
💡 Model shows good potential for integration in clinical decision support systems.

---

## 📌 Future Work

- 🧠 Apply ensemble models like XGBoost
- 📈 Hyperparameter tuning with GridSearchCV
- 🌐 Deploy using Flask/Streamlit
- 🏥 Use real-world EHR data for validation

---

## 🧑‍💻 Author

**Shivraj Chourasia**  
📧 [work.shivraj.chourasia@gmail.com](mailto:work.shivraj.chourasia@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/shivraj-chourasia-917310344)  
💻 [GitHub](https://github.com/Shivrajchourasia)

---


