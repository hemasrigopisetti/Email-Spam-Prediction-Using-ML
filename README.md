# 📌 Email Spam Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8-blue)
![Accuracy](https://img.shields.io/badge/Accuracy-97%25-brightgreen)
![Status](https://img.shields.io/badge/Project-Completed-success)
![Domain](https://img.shields.io/badge/Domain-NLP-orange)

---

## 📌 Overview

This project is a **Machine Learning-based Email Spam Detection System** that classifies email messages as **Spam or Ham (Not Spam)** using Natural Language Processing (NLP) techniques.

It is integrated with a **Flask-based web application** that allows users to input email text and get real-time predictions.

---

## 🎯 Objectives

* Detect spam emails accurately using ML models
* Apply NLP techniques for text classification
* Build a user-friendly web interface
* Provide real-time predictions

---

## 🚀 Features

✔ Email text preprocessing
✔ Spam/Ham classification
✔ TF-IDF vectorization
✔ Trained ML model using Scikit-learn
✔ Flask-based web application
✔ Real-time prediction system
✔ Clean and simple UI

---

## 🧠 Workflow

User Input → Text Preprocessing → TF-IDF Vectorization → ML Model → Prediction (Spam / Ham)

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:** NumPy, Pandas, Scikit-learn
* **Framework:** Flask
* **Concepts:** NLP, Text Classification

---

## 📂 Project Structure

```bash
Email-Spam-Prediction/
│
├── backend/
│   └── model_training.ipynb
│
├── frontend/
│   └── app.py
│
├── dataset/
│   └── mail_data.csv
│
├── models/
│   ├── spam_model.pkl
│   └── vectorizer.pkl
│
├── ui_screenshots/
│   ├── loginpage.png
│   ├── input.png
│   └── output.png
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 📊 Dataset

* Contains labeled email messages
* Classes:

  * 0 → Spam
  * 1 → Ham (Not Spam)

---

## ⚙️ How It Works

1. Input email text
2. Perform text preprocessing
3. Convert text into numerical form using TF-IDF
4. Apply trained ML model
5. Predict whether email is Spam or Ham

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/hemasrigopisetti/Email-Spam-Prediction.git
cd Email-Spam-Prediction
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
python frontend/app.py
```

---

## 📊 Results

### ✅ Model Performance

* 🎯 **Accuracy:** 97%
* 📌 High precision in spam detection
* 📌 Efficient classification of spam and legitimate emails

### 📈 Evaluation Metrics

* Precision
* Recall
* F1-Score

---

## 🌐 Web Application

The project includes a Flask-based web application with:

* Login Page
* Input Text Area
* Prediction Output Display

---

## 📸 Application Screenshots

### 🔐 Login Page

![Login](ui_screenshots/loginpage.png)

### ✉️ Input Page

![Input](ui_screenshots/input.png)

### ✅ Output Result

![Output](ui_screenshots/output.png)

---

## 🔍 Future Enhancements

* Improve accuracy using Deep Learning (LSTM, BERT)
* Deploy on cloud platforms
* Enhance UI design
* Integrate with email services

---

## 📁 Dataset Note

Dataset is included in this project for training and testing purposes.

---

## 👩‍💻 Author

**Hemasri Gopisetti**

B.Tech (CSM) | ML Enthusiast

---

## ⭐ Support

If you like this project, please ⭐ star the repository!
