Customer Churn Prediction using Machine Learning & Flask
📌 Project Overview

Customer Churn Prediction is a Machine Learning project that predicts whether a telecom customer is likely to leave the company's services. The project uses the IBM Telco Customer Churn Dataset, performs data preprocessing and exploratory data analysis (EDA), trains a Random Forest Classifier, and deploys the trained model through a Flask web application for real-time predictions.

🎯 Problem Statement

Customer retention is one of the biggest challenges for telecom companies. Acquiring a new customer is often more expensive than retaining an existing one. This project helps identify customers who are at risk of leaving, allowing businesses to take proactive measures such as personalized offers, discounts, or improved customer support.

📊 Dataset

Dataset: IT Customer Churn Dataset

The dataset contains customer information such as:

Gender
Senior Citizen
Partner
Dependents
Tenure
Phone Service
Internet Service
Online Security
Online Backup
Device Protection
Tech Support
Streaming TV & Movies
Contract Type
Paperless Billing
Payment Method
Monthly Charges
Total Charges
Churn (Target Variable)
⚙️ Project Workflow
Data Collection
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Label Encoding
Train-Test Split
Model Training
Model Evaluation
Model Deployment using Flask
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Joblib
Flask
HTML
CSS
Bootstrap
📈 Exploratory Data Analysis

Several visualizations were created to understand customer behavior, including:

Churn Distribution
Contract Type Analysis
Internet Service Distribution
Monthly Charges Distribution
Tenure Analysis
Correlation Heatmap
Pair Plot
Feature-wise Churn Comparison
Key Insights
Customers with Month-to-Month contracts have a higher churn rate.
Customers with longer tenure are less likely to churn.
Higher monthly charges are associated with increased churn.
Fiber Optic customers show relatively higher churn.
Customers with additional services such as Online Security and Tech Support are more likely to stay.
🤖 Machine Learning Model

Algorithm Used:

Random Forest Classifier
Why Random Forest?
High prediction accuracy
Handles both numerical and categorical data
Reduces overfitting using multiple decision trees
Robust and reliable for classification problems
📊 Model Evaluation

The model was evaluated using:

Accuracy Score
Precision
Recall
F1 Score
Confusion Matrix

The trained model achieved strong performance in predicting customer churn and generalized well on unseen data.

🌐 Flask Web Application

A user-friendly web application was developed using Flask.

Features
Interactive customer input form
Real-time churn prediction
Prediction confidence score
Clean and responsive user interface
Error handling for invalid inputs
📂 Project Structure
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
🚀 How to Run the Project
1. Clone the Repository
git clone https://github.com/your-username/Customer-Churn-Prediction.git
2. Navigate to the Project Folder
cd Customer-Churn-Prediction
3. Install Dependencies
pip install -r requirements.txt
4. Run the Flask Application
python app.py
5. Open in Browser
http://127.0.0.1:5000
📌 Future Improvements
Hyperparameter tuning for improved performance
Model explainability using SHAP
Docker deployment
Cloud deployment (AWS/Render/Heroku)
User authentication and database integration
💼 Business Impact

This project enables telecom companies to:

Identify customers at risk of churning
Improve customer retention strategies
Reduce revenue loss
Enhance customer satisfaction through proactive engagement
👨‍💻 Author

Varun Singh

B.Tech CSE (3rd Year)

Interested in Machine Learning, Data Science, and Artificial Intelligence.

⭐ If you found this project useful, don't forget to Star the repository!
