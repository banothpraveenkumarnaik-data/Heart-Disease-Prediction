# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview
This project implements a machine learning–based classification system to predict the presence of heart disease in patients. Early detection is crucial in the healthcare domain, and this system is designed to support clinical decision-making by providing accurate and reliable predictions.

The study evaluates multiple classification algorithms and identifies the most effective model for this task.

## 🎯 Objectives
- Predict whether a patient is likely to have heart disease  
- Compare different machine learning models  
- Select the most accurate and reliable classifier  
- Minimize false negatives by prioritizing recall  

## 🗂 Dataset & Preprocessing
The dataset was processed using:
- Missing value handling  
- Categorical feature encoding  
- Feature scaling / normalization  
- Outlier analysis (tested but not applied due to performance reduction)

## 🧠 Models Implemented
Logistic Regression, SVM, Random Forest, Gradient Boosting, XGBoost, and Voting Ensemble.

## 📊 Evaluation Metrics
Accuracy, Precision, Recall, F1-Score, and Cross-Validation.

## 🏆 Best Performing Model
**Gradient Boosting Classifier**

Accuracy: **91.67%**  
Recall: **1.00**  
F1-Score: **0.91**

## ⚙️ Technologies Used
Python, Scikit-learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook.

## 🚀 How to Run
```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
pip install -r requirements.txt
jupyter notebook
