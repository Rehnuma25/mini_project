# 🔬 Heart Disease Prediction using Machine Learning

****This project aims to predict the presence of heart disease in a patient using machine learning techniques, based on various health-related inputs
such as age, blood pressure, cholesterol levels, and more.

---

## 📂 Dataset Details

- **Dataset Name:** Heart Disease UCI Dataset
- **Source:** [Kaggle – Heart Disease UCI Dataset]
- **Features:** 13 input features
- **Target Variable:** "target"(1 = Heart disease present, 0 = No heart disease)

---

## 🛠️ Technologies Used

- **Python 3.11
- **Jupyter Notebook**
- ***Libraries:***
  - pandas, numpy
  - matplotlib, seaborn (for visualization)
  - scikit-learn (for machine learning)
  - ipywidgets, IPython.display (for interactive input and styled output)

---

##### 🎯 Project Features

- Data loading and cleaning
- Feature scaling using `StandardScaler`
- Training using `RandomForestClassifier`
- Styled prediction results using red (🔴) or green (🟢) output #(use keyboard)
- Input validation
- Model accuracy display

---

## 🧠 How It Works
1. The user enters 13 values in this format:
   ```python
   [age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal]
   💗 Then it run perfectly...
   
   ******The result is displayed clearly with large, bold colored text using HTML styling:
  🔴 You may have heart disease.
  🟢 You are safe.

  🎯🎯🎯 SO this is my simple mini project...........
