# Fraud-detection-using-Machine-Learning

A simple and interactive **Streamlit web application** that predicts whether a financial transaction is **fraudulent** or **legitimate** using a trained Machine Learning model.

---

##  Overview

This project demonstrates how machine learning can be used to detect fraudulent financial transactions.  
Users can input transaction details (like amount, balance, type of transaction, etc.) through a web interface, and the app will predict whether the transaction is likely to be **fraudulent (1)** or **legitimate (0)**.

---

##  Features

- 🧾 User-friendly web interface built with **Streamlit**  
- 💡 Real-time fraud prediction using a pre-trained ML model  
- 📦 Uses a serialized model file (`fraud_detection_pipeline.pkl`)  
- 📊 Developed and analyzed in **Python / Jupyter Notebook**

---
## 🗂️ Project Structure

fraud-detection-app/
│
├── fraud_detection.py # Main Streamlit app file
├── fraud_detection_pipeline.pkl # Pre-trained model file
├── AIML Dataset.csv # Dataset used for model training (optional)
├── analysis_model.ipynb # Model training and analysis notebook
├── requirements.txt # Dependencies
└── README.md # Project documentation

---

## 🚀 How to Run Locally

### 1️⃣ Clone this repository
```bash
git clone https://github.com/<your-username>/fraud-detection-app.git
cd fraud-detection-app

pip install -r requirements.txt

streamlit run fraud_detection.py



