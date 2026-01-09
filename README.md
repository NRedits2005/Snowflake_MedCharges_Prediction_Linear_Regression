# 🏥 Insurance Charges Prediction using Linear Regression

## 📌 Overview  
This project focuses on predicting **medical insurance charges** using the **Linear Regression** algorithm. The model learns patterns from demographic and lifestyle data to estimate healthcare costs accurately.

---

## 📊 Dataset Description  
The dataset contains individual insurance records with the following attributes:

- 🧓 **Age** – Age of the insured person  
- 🚻 **Sex** – Gender (male / female)  
- ⚖️ **BMI** – Body Mass Index  
- 👨‍👩‍👧 **Children** – Number of dependents  
- 🚬 **Smoker** – Smoking status (yes / no)  
- 🌍 **Region** – Residential area  
- 💰 **Charges** – Medical insurance cost (target variable)

---

## 🧠 Model Used  
- **Linear Regression**
  - Supervised machine learning algorithm  
  - Models the relationship between features and insurance charges  
  - Simple, interpretable, and effective for continuous value prediction  

---

## 🔄 Data Processing  
- Categorical features converted into numerical format  
- Features and target variable separated  
- Data split into training and testing sets  

---

## 📈 Model Performance  
- Evaluated using:
  - 📉 Mean Squared Error (MSE)  
  - 📐 Root Mean Squared Error (RMSE)  
  - 🎯 R² Score  

The model achieves a **good prediction accuracy**, with smoking status and BMI being major contributing factors.

---

## 🔮 Prediction  
The trained model can predict insurance charges for new individuals based on their personal and lifestyle details.

---

## 🚀 Key Insights  
- 🚬 Smokers incur significantly higher charges  
- ⚖️ Higher BMI increases insurance cost  
- 🧓 Age positively correlates with charges  

---

## 🛠️ Technologies Used  
- 🐍 Python  
- 📦 Pandas & NumPy  
- 🤖 Scikit-learn  

---

## ✨ Conclusion  
Linear Regression provides an effective baseline model for predicting insurance charges and offers clear interpretability, making it suitable for real-world healthcare cost analysis.
