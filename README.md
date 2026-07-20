# 📊 Customer Churn Prediction using Machine Learning & Flask

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20App-black?logo=flask)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Project Overview

Customer Churn Prediction is a Machine Learning project that predicts whether a telecom customer is likely to leave the company's services. This project uses the **IBM Telco Customer Churn Dataset**, performs data preprocessing and exploratory data analysis (EDA), trains a **Random Forest Classifier**, and deploys the trained model using **Flask** for real-time customer churn prediction.

---

## 🎯 Problem Statement

Customer retention is one of the biggest challenges for telecom companies. Acquiring a new customer is often more expensive than retaining an existing one. This project helps businesses identify customers who are at risk of leaving so they can take proactive measures such as discounts, personalized offers, or improved customer support.

---

## 📂 Dataset

**Dataset:** IT Customer Churn Dataset

The dataset contains customer information including:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV & Movies
- Contract Type
- Paperless Billing
- Payment Method
- Monthly Charges
- Total Charges
- Churn (Target Variable)

---

## ⚙️ Project Workflow

1. Data Collection
2. Data Cleaning
3. Data Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Encoding
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Model Deployment using Flask

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Flask
- Joblib
- HTML
- CSS
- Bootstrap

---

## 📊 Exploratory Data Analysis (EDA)

Several visualizations were created to understand customer behavior and identify patterns affecting churn.

### Key Insights

- Customers with Month-to-Month contracts have a higher churn rate.
- Customers with longer tenure are less likely to churn.
- Higher monthly charges increase the likelihood of churn.
- Fiber Optic customers show comparatively higher churn.
- Customers with Online Security and Tech Support services are more likely to remain with the company.

---

## 🤖 Machine Learning Model

### Algorithm Used

- Random Forest Classifier

### Why Random Forest?

- High prediction accuracy
- Handles both numerical and categorical features
- Reduces overfitting using multiple decision trees
- Performs well on classification problems

---

## 📈 Model Evaluation

The model was evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

The trained model successfully predicts customer churn with high accuracy on unseen data.

---

## 🌐 Flask Web Application

The trained model is deployed using Flask to provide real-time customer churn prediction.

### Features

- User-friendly interface
- Customer information input form
- Real-time prediction
- Prediction confidence score
- Responsive design
- Input validation

---

## 📁 Project Structure

```text
Customer_Churn_Prediction/
│
├── app.py
├── churn_model.pkl
├── label_encoders.pkl
├── feature_order.pkl
├── requirements.txt
│
├── templates/
│   └── index.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
│
├── notebooks/
│   └── IT_Customer_Churn_Prediction.ipynb
│
└── README.md
```

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Customer-Churn-Prediction.git
```

### Navigate to the Project Directory

```bash
cd Customer-Churn-Prediction
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Run the Flask Application

```bash
python app.py
```

### Open in Browser

```
http://127.0.0.1:5000
```

---

## 📌 Future Enhancements

- Hyperparameter tuning
- SHAP-based model explainability
- Docker support
- Cloud deployment (AWS / Render / Azure)
- Database integration
- User authentication

---

## 💼 Business Impact

This project enables telecom companies to:

- Predict customer churn before it occurs
- Improve customer retention strategies
- Reduce revenue loss
- Increase customer satisfaction through proactive engagement

---

## 👨‍💻 Author

**Varun Singh**

B.Tech CSE (3rd Year)

Interested in **Machine Learning, Data Science, Artificial Intelligence, and Software Development.**

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.
