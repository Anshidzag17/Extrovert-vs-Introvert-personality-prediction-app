# Extrovert-vs-Introvert-personality-prediction-app

This project predicts whether a person is an **Extrovert** or **Introvert** based on various behavioral traits. It uses a machine learning model (KNN) and is deployed using Flask.

## 🔍 Overview

The application takes user input through a web form and predicts the personality type based on:
- Time spent alone
- Stage fear
- Attendance at social events
- Frequency of going outside
- Whether they feel drained after socializing
- Size of their friend circle
- Social media posting frequency

## 🛠 Technologies Used

- Python
- Flask (Web Framework)
- Scikit-learn (for model training)
- HTML (for frontend)
- Pickle (for model serialization)

## 📁 Project Structure
```bash
├── flask1.py # Flask application
├── knn_model.pkl # Trained ML model
├── templates/
│ └── index.html # Frontend form for input and output
├── Extrovert_vs_Introvert.ipynb # Jupyter Notebook for model training
└── README.md # Project documentation
```

