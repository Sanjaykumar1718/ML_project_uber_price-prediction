# ML_project_uber_price-prediction
# 🚗 Weekly Rides Prediction Web App

This is a simple machine learning web application built using **Flask** that predicts the number of weekly rides based on user input features such as age, distance, and rating (or any custom features your model uses).

## 📌 Features

- Built with Flask (Python)
- Uses a pre-trained Linear Regression model (`model.pkl`)
- User-friendly HTML form to input data
- Displays prediction on the same page

---

## 🧠 Machine Learning Model

- **Model used**: `LinearRegression` from `scikit-learn`
- **Training input features**: Example — Age, Distance, Rating (customize this based on your training)
- **Target**: Predicted number of weekly rides
- **Serialized model**: Saved as `model.pkl` using Python's `pickle` module

---

## 🏗 Project Structure

machine-learning-project/
│
├── app.py # Flask application
├── model.pkl # Trained ML model
├── templates/
│ └── index.html # HTML frontend
├── static/
│ └── style.css # Optional CSS styling
├── README.md # Project documentation
└── requirements.txt # Python dependencies

# required libraries:
flask
numpy
scikit-learn
pandas
