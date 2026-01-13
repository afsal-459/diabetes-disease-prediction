# Diabetes Disease Prediction using Logistic Regression

## 📌 Project Overview
This project focuses on predicting whether a patient is diabetic or not using medical attributes.  
A Logistic Regression classification model is built, trained, and evaluated on a standard diabetes dataset to demonstrate a complete machine learning pipeline.

The project covers data preprocessing, model training, evaluation using classification metrics, and prediction for new patient data.

---

## 🎯 Problem Statement
To predict the presence of diabetes in a patient based on medical measurements using a supervised machine learning classification algorithm.

---

## 📂 Dataset
- **Dataset Name:** Pima Indians Diabetes Dataset  
- **Source:** National Institute of Diabetes and Digestive and Kidney Diseases  
- **Target Variable:** `Outcome`  
  - `0` → Not Diabetic  
  - `1` → Diabetic  

### Features Used:
- Pregnancies  
- Glucose  
- BloodPressure  
- SkinThickness  
- Insulin  
- BMI  
- DiabetesPedigreeFunction  
- Age  

---

## ⚙️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## 🔄 Project Workflow
1. Import required libraries  
2. Load and explore the dataset  
3. Handle missing and invalid values  
4. Define input features (X) and target variable (y)  
5. Split data into training and testing sets  
6. Train Logistic Regression model  
7. Evaluate model using classification metrics  
8. Predict diabetes for new patient data  

---

## 🤖 Model Used
**Logistic Regression**

Logistic Regression is a classification algorithm used to predict binary outcomes.  
In this project, it estimates the probability of diabetes based on medical features and classifies patients accordingly.

---

## 📊 Model Evaluation
The model is evaluated using:
- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report (Precision, Recall, F1-score)**

Special attention is given to **recall**, as false negatives are critical in medical diagnosis scenarios.

---

## 🧪 Sample Prediction
Example patient data is provided to demonstrate real-world prediction:

- The model outputs:
  - Predicted class (Diabetic / Not Diabetic)
  - Probability of having diabetes

This helps in understanding both the decision and confidence level of the model.

---

## 📁 Project Structure
