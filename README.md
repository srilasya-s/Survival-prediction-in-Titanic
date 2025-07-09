# Survival-prediction-in-Titanic
# 🛳️ Titanic Survival Prediction

This project applies machine learning techniques to predict passenger survival on the Titanic using the classic [Kaggle Titanic dataset](https://www.kaggle.com/competitions/titanic). It showcases a complete ML workflow including data analysis, preprocessing, feature engineering, model training, and evaluation.

---

## Problem Statement

Predict whether a passenger survived the Titanic disaster based on features such as age, class, gender, fare, and family connections.

---


##  Techniques Used

- **Exploratory Data Analysis (EDA)** using `pandas`, `seaborn`, `matplotlib`
- **Feature Engineering**:  
  - Handling missing values  
  - One-hot encoding categorical variables  
  - Creating new features (`Title`, `FamilySize`, etc.)
- **ML Models**:  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - Support Vector Machine
- **Model Evaluation**:  
  - Accuracy  
  - Confusion Matrix  
  - Cross-validation

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

git clone https://github.com/srilasya-s/Survival-prediction-in-Titanic.git
cd Survival-prediction-in-Titanic

### 2️⃣ Install Dependencies
Skip this step if you're running in Jupyter with your own environment.
pip install -r requirements.txt

### 3️⃣ Launch the Notebook
jupyter notebook titanic.ipynb


Dataset Overview
Source: Kaggle Titanic Competition

Key features:

Pclass – Ticket class

Sex – Gender

Age – Age of the passenger

SibSp – Number of siblings/spouses aboard

Parch – Number of parents/children aboard

Fare – Passenger fare

Embarked – Port of embarkation

Survived – Target variable (0 = No, 1 = Yes)

🚧 Future Improvements
Try advanced models like XGBoost, LightGBM, or Stacking Classifiers

Perform hyperparameter tuning

Deploy the model as a Streamlit web app for interactive predictions

🤝 Contact & Collaboration
👤 Sri Lasya S
🔗 [LinkedIn](https://www.linkedin.com/in/srilasyas/)
🌐 Portfolio (srilasyaportfolio.netlify.app)

Feel free to open issues, suggest improvements, or collaborate!

