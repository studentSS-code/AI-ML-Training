# AI-ML-Training
# Diabetes Prediction using Support Vector Machine (SVM)

This repository contains a machine learning project that predicts whether a patient has diabetes based on specific diagnostic measurements. The model is built using Python and the Scikit-Learn library.

## 🚀 Project Overview
The goal of this project is to create a classification model that can accurately identify diabetic patients. It uses a dataset containing several medical predictor variables and one target variable (`Outcome`).

## 📊 Dataset Features
The dataset includes the following variables:
* **Pregnancies**: Number of times pregnant
* **Glucose**: Plasma glucose concentration
* **BloodPressure**: Diastolic blood pressure (mm Hg)
* **SkinThickness**: Triceps skin fold thickness (mm)
* **Insulin**: 2-Hour serum insulin (mu U/ml)
* **BMI**: Body mass index
* **DiabetesPedigreeFunction**: Diabetes pedigree function
* **Age**: Age in years
* **Outcome**: Class variable (0 or 1)

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Scikit-Learn
* **Environment:** Google Colab / Jupyter Notebook

## 📈 Model Performance
The model was trained using a **Support Vector Classifier (SVC)** with a linear kernel.
* **Accuracy:** ~76%
* **Scaling:** Data was standardized using `StandardScaler` for optimal SVM performance.

## ⚙️ How to Use
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
