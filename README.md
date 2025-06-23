# 🍪 Sweet or Savory Predictor

Welcome to the **Sweet or Savory Predictor** — a web application that uses a machine learning model to determine whether a food is **sweet** or **savory** based on its ingredient quantities.

---

## 📌 Overview

This project includes:

* **🔍 Model Training:** Classifies food as sweet or savory using ingredient data
* **⚙️ Flask API:** Backend API built with Flask to handle predictions
* **🖥️ Frontend:** Simple web interface for input and result display

---

## 📁 Project Structure

| File               | Description                               |
| ------------------ | ----------------------------------------- |
| `app.py`           | Flask app serving the prediction endpoint |
| `model.py`         | Script to train and save the ML model     |
| `index.html`       | Frontend interface for user input         |
| `requirements.txt` | Python dependencies                       |
| `.gitignore`       | Files ignored by Git                      |

---

## 🚀 How to Use

1. **Input Ingredients**
   Enter quantities of **flour, sugar, salt, butter** in grams (e.g., `100, 50, 5, 20`)

2. **Submit the Form**
   Click **"Predict"** to send the data to the Flask server

3. **View Result**
   The prediction (Sweet or Savory) will be shown below the form

---

## ⚙️ Running the App

```bash
# Clone the repository
git clone https://github.com/Ushna-Nadeem/mlops-deployment-task.git
cd mlops-deployment-task

# Install dependencies
pip install -r requirements.txt

# Run the Flask server
python app.py
```

Visit `http://localhost:5000` in your browser to interact with the app.

---

## ✅ Features

* Real-time food type prediction
* Lightweight, easy-to-use interface
* Modular backend and ML code for scalability
