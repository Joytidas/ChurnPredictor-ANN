## ChurnPredictor-ANN
Customer Churn Prediction using Artificial Neural Networks (ANN) involves building a model to forecast whether a customer is likely to leave or continue using a service. The ANN learns from historical data, considering factors like usage patterns, customer interactions, and feedback to make predictions.
ChurnPredictor-ANN/
│
├── dataset/
│   └── Churn_Modelling.csv        # Dataset file
│
├── churn_prediction_ann.ipynb     # Jupyter Notebook (recommended)
├── churn_prediction_ann.py        # Python script (optional)
├── README.md                      # Project description
└── requirements.txt               # Required libraries
# Churn Prediction using Artificial Neural Network (ANN)

This project uses an Artificial Neural Network (ANN) built with TensorFlow and Keras to predict customer churn based on customer demographic and account information.

## 📌 Problem Statement
Predict whether a customer is likely to churn (leave) based on their behavior and profile.

## 🚀 Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

## 📂 Dataset
Dataset used: `Churn_Modelling.csv` (Bank Customer Churn Dataset)  
Example features include:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Estimated Salary

## 📈 Model Architecture
- Input Layer
- Two Hidden Layers (ReLU activation)
- Output Layer (Sigmoid activation)

📊 Results
The model achieves an accuracy of approximately 86-87% on the test set.
