🎓 Academic Intelligence System
🚀 CGPA Predictor • Smart Planner • IQ Test

An AI-powered EdTech web application that predicts student performance, generates personalized study plans, and evaluates cognitive ability through a gamified IQ system.

🌐 Live Demo

🔗 https://dashboard-for-study-4.onrender.com/

⚠️ Note: App may take a few seconds to load due to server warm-up.

📖 Overview

The Academic Intelligence System is designed to help students improve their academic performance using Machine Learning and Data Analytics.

It provides:

📊 CGPA Prediction

📅 Smart Study Planner

🧠 IQ Test with Ranking System

📈 Performance Tracking

✨ Key Features
📊 CGPA Prediction

Predicts future CGPA using ML models

Based on:

Historical performance

Study patterns

Real-time results

📅 Smart Mission Planner

Personalized daily study schedule

Detects at-risk students

Adaptive time optimization

🧠 IQ Test & Ranking

Gamified levels:

Genin → Chūnin → Jōnin → Kage

Tracks cognitive growth

Visual analytics dashboard

🧠 Machine Learning

Algorithms Used:

Random Forest (94.2% accuracy)

Linear Regression

Neural Network

Dataset:

100+ student records

Libraries:

pandas

numpy

scikit-learn

statsmodels

🏗️ Project Structure
cgpa-prediction-system/
│
├── app.py
├── iq_data.py
├── model.pkl
├── data_preprocessing.py
├── model_training.py
├── predictions.csv
├── UG_Student_CGPA_Prediction.xlsx
│
├── notebook/
│
├── templates/
│   ├── index.html
│   ├── result.html
│   ├── iq_dashboard.html
│   ├── iq_test.html
│   └── planner.html
│
├── static/
├── requirements.txt
├── Dockerfile
└── README.md
⚙️ Tech Stack
🔹 Backend

Python

Flask

Gunicorn

🔹 Frontend

HTML5

Tailwind CSS

Jinja2

🔹 Machine Learning

scikit-learn

pandas

numpy

🔹 Deployment

Render

📊 Model Performance
Model	Accuracy
Random Forest	94.2%
Neural Network	91.8%
Linear Regression	87.5%
🛠️ Installation
# Clone the repository
git clone https://github.com/kishan-p-code/dashboard-for-study-/tree/main

# Go to project folder
cd dashboard-for-study-

# Install dependencies
pip install -r requirements.txt

# Run application
python app.py

👉 Open: http://localhost:5000

🚀 Future Improvements

🧠 Advanced AI models (Transformers)

📱 Mobile App (Android / iOS)

☁️ Cloud Deployment (AWS / Azure)

📊 Long-term analytics tracking

🤝 Contributing

Contributions are welcome!
Fork the repo and create a pull request.
