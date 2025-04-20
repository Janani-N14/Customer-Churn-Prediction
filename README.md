# Customer-Churn-Prediction
This project predicts whether a bank employee is likely to stay or leave the company, based on key employment and personal attributes. Built using a trained Artificial Neural Network (ANN) model, it features an interactive web interface developed using Streamlit.

🔍 Problem Statement
Employee churn is a significant concern for businesses. Retaining valuable employees is critical for growth, productivity, and reducing recruitment/training costs. This app helps HR and management teams assess churn risk for each employee based on data-driven predictions.

🚀 Features
Predicts the probability of an employee churning.

Uses an ANN model trained on historical data.

User-friendly Streamlit interface.

Scalable solution using saved encoders and scalers.

🛠️ Tech Stack
Frontend: Streamlit

Backend: TensorFlow / Keras

Machine Learning: ANN (Artificial Neural Network)

Preprocessing: Scikit-learn (StandardScaler, LabelEncoder, OneHotEncoder)

Languages: Python

Data Handling: Pandas, NumPy

📂 Files Included
app.py - Main Streamlit application.

model.h5 - Trained ANN model.

label_encoder_gender.pkl - Gender encoder.

onehot_encoder_geo.pkl - Geography encoder.

scaler.pkl - Feature scaler.

📈 Input Parameters
Geography: Country or region of the employee.

Gender: Male/Female.

Age: Employee's age.

Balance: Account balance.

Credit Score: Financial credit rating.

Estimated Salary: Predicted yearly salary.

Tenure: Number of years in the company.

Number of Products: Services/products employee is using.

Has Credit Card: Binary indicator.

Is Active Member: Binary indicator of active status.

✅ Output
Churn Probability: A score between 0 and 1.

Interpretation:

If probability > 0.5 → Employee is likely to leave.

Else → Employee is likely to stay.
