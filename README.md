📌 Email Spam Prediction using Machine Learning
🚀 Project Overview

This project is a Machine Learning-based Email Spam Detection System that classifies email messages as Spam or Ham (Not Spam) using Natural Language Processing (NLP) techniques.

The system is integrated with a Flask-based web application that allows users to log in and check email messages in real time.

🎯 Objective

To detect spam emails accurately using ML models

To apply NLP techniques for text classification

To build a user-friendly web interface

To provide real-time predictions

🧠 Workflow of the Project
User Input → Text Preprocessing → TF-IDF Vectorization → ML Model → Prediction (Spam / Ham)
📂 Project Structure
Email-Spam-Prediction/
│
├── backend/
│   └── model_training.ipynb        # Model building & training
│
├── frontend/
│   └── app.py                     # Flask web application
│
├── dataset/
│   └── mail_data.csv              # Dataset
│
├── models/
│   ├── spam_model.pkl             # Trained ML model
│   └── vectorizer.pkl             # TF-IDF vectorizer
│
├── ui_screenshots/                # Application UI
│   ├── loginpage.png
│   ├── input.png
│   └── output.png
│
├── requirements.txt
├── .gitignore
└── README.md
📊 Dataset Details

Dataset contains labeled email messages

Categories:

Spam (0)

Ham (1)

Used for training and testing the model

⚙️ Technologies Used
💻 Programming Language

Python

📚 Libraries

NumPy

Pandas

Scikit-learn

Flask

🧠 ML Techniques

Text Preprocessing

TF-IDF Vectorization

Logistic Regression / Naive Bayes

🔍 Features

✔️ Email text preprocessing
✔️ Spam/Ham classification
✔️ Trained ML model saved using Pickle
✔️ Flask-based web application
✔️ User-friendly interface
✔️ Real-time prediction
✔️ UI screenshots included

🧪 Model Performance

Algorithm Used:

Logistic Regression

Multinomial Naive Bayes

Evaluation Metrics:

Accuracy: ⭐ ~97% (or your actual value)

Precision

Recall

F1-Score

👉 The model performs well in distinguishing spam and legitimate emails with high accuracy.

🌐 Web Application

The project includes a Flask-based web app with:

Login Page

Input Text Area

Prediction Output Display

📸 Application Screenshots
🔐 Login Page

✉️ Input Page

✅ Output Result

▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/Email-Spam-Prediction.git
cd Email-Spam-Prediction
2️⃣ Install Requirements
pip install -r requirements.txt
3️⃣ Run the Application
python frontend/app.py
4️⃣ Open in Browser
http://127.0.0.1:5000/
📈 Future Enhancements

Improve accuracy using Deep Learning (LSTM, BERT)

Deploy the application on cloud platforms

Enhance UI design

Integrate with email services (Gmail API)

👩‍💻 Author

Hemasri Gopisetti
B.Tech (CSM)
Full Stack Developer | ML Enthusiast

⭐ Support

If you like this project, please ⭐ star the repository!
