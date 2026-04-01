# 🚢 Titanic Survival Prediction

This project uses machine learning to predict whether a passenger survived the Titanic disaster based on features like age, gender, class, and fare.

---

## 📌 Project Overview
The goal of this project is to analyze passenger data and build predictive models to determine survival outcomes. It demonstrates a complete data science workflow including data preprocessing, feature engineering, model training, and evaluation.

---

## 🎯 Objectives
- Predict survival (0 = Not Survived, 1 = Survived)
- Identify key factors influencing survival
- Compare multiple machine learning models

---

## 📊 Dataset
- Source: Kaggle Titanic Dataset
- Total Records: 891 passengers
- Features: Age, Sex, Pclass, Fare, Embarked, SibSp, Parch, etc.

---

## ⚙️ Steps Performed

### 1. Data Preprocessing
- Handled missing values (Age, Embarked)
- Dropped Cabin due to excessive missing data

### 2. Feature Engineering
- Created new features:
  - FamilySize
  - IsAlone
  - Title (Mr, Mrs, etc.)
  - AgeGroup, FareGroup

### 3. Data Encoding
- Label Encoding for categorical variables
- One-hot encoding for Embarked and Pclass

### 4. Model Building
Trained multiple models:
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

### 5. Model Evaluation
- Metrics used:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- Cross-validation applied for reliable results

---

## 🏆 Results
- Best Model: Random Forest
- Achieved strong performance with balanced accuracy and generalization
- Ensemble models performed better than individual models

---

## 📈 Key Insights
- Females had higher survival chances than males
- Higher-class passengers had better survival rates
- Family size influenced survival probability

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📂 Project Structure
