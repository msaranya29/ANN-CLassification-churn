# ANN-Based Customer Churn Prediction System

This project implements an Artificial Neural Network (ANN) to predict whether a customer is likely to churn (exit) or not based on demographic and financial attributes. The system uses proper data preprocessing, encoding, scaling, and a trained ANN model built using TensorFlow and Keras.

---

## Problem Statement
Customer churn is a critical problem for businesses. Predicting whether a customer will leave helps organizations take preventive actions to improve customer retention. This project aims to build a classification model that predicts customer churn using historical data.

---

## Features
- ANN-based binary classification
- Label Encoding for Gender
- One-Hot Encoding for Geography
- Feature Scaling using StandardScaler
- Trained ANN model saved as `.h5`
- Encoders and scaler saved using `pickle`
- Separate notebooks for training and prediction
- Easily extendable for deployment (Streamlit / Flask)

---

## Tech Stack
- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Pickle
- Jupyter Notebook

---

## Project Structure
```bash
ANN/
├── app.py # Streamlit application 
├── experiments.ipynb # Model training & experimentation
├── prediction.ipynb # Prediction pipeline
│
├── data/ # Dataset directory
│ └── Churn_Modelling.csv # Customer churn dataset
│
├── models/ # Trained models & preprocessing objects
│ ├── model.h5 # Trained ANN model
│ ├── scaler.pkl # Feature scaler
│ ├── label_encoder_gender.pkl # Gender label encoder
│ └── onehot_encoder_geo.pkl # Geography one-hot encoder
│
├── requirements.txt # Python dependencies
├── .gitignore # Git ignore rules
└── README.md # Project documentation
```




---

## ⚙️ Installation & Setup

### Clone the Repository
```bash
git clone https://github.com/anya29/ANN-CLassification-churn.git
cd ANN-CLassification-churn
```
### Create Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the Streamlit application:
```bash
streamlit run app.py
```




