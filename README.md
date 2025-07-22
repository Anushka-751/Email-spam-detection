# 📧 Email Spam Detector with Machine Learning and Streamlit

This project is a simple yet powerful web app built using **Python**, **Scikit-learn**, and **Streamlit** that detects whether a given email message is **Spam or Ham**.

## 🚀 Features

- Classifies text as **SPAM** or **HAM** (not spam)
- Built using:
  - Machine Learning (Multinomial Naive Bayes)
  - Scikit-learn
  - Streamlit UI
- Fully deployable via Streamlit Cloud

## 🛠️ Technologies Used

- Python 3
- Pandas
- Scikit-learn
- Streamlit
- Joblib

## 📊 Model Accuracy

- **Accuracy**: 97.84%
- **Precision (Spam)**: 91%
- **Recall (Spam)**: 93%
- Trained on the popular `spam.csv` dataset.

## 📁 Project Structure
email-spam-detector/
├── app.py ← Streamlit web app
├── model_training.py ← Model training script
├── spam.csv ← Dataset
├── spam_model.pkl ← Trained ML model
├── vectorizer.pkl ← TF-IDF vectorizer
└── requirements.txt ← Python dependencies


## ▶️ Run the App Locally

```bash
pip install -r requirements.txt
streamlit run app.py
