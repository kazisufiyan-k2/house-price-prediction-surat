# 🏠 Surat House Price Prediction System

A Machine Learning-based web application that predicts house prices in Surat based on user inputs like area, BHK, square feet, and amenities.

---

## 🚀 Live Demo

🔗 Coming Soon (Deploy on Render)

---

## 📌 Features

* 📊 Predict house prices using trained ML model
* 🧠 Built with Scikit-learn
* 🌐 User-friendly web interface using Flask
* 📍 Area & locality-based prediction
* ⚡ Fast and real-time results

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS
* **Backend:** Flask
* **Machine Learning:** Scikit-learn, NumPy, Joblib
* **Deployment:** Render
* **Language:** Python

---

## 📂 Project Structure

```
house-price-prediction-surat/
│
├── house_price_app/
│   ├── app.py
│   ├── final_deployment_model.pkl
│   ├── requirements.txt
│   ├── static/
│   │   └── style.css
│   └── templates/
│       └── index.html
│
├── requirements.txt
├── runtime.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/kazisufiyan-k2/house-price-prediction-surat.git
cd house-price-prediction-surat
```

---

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run the Application

```bash
python house_price_app/app.py
```

---

### 5️⃣ Open in Browser

```
http://127.0.0.1:5000/
```

---

## 🤖 Machine Learning Model

* Algorithm Used: Linear Regression (or your model)
* Data Preprocessing: Feature Engineering, Encoding
* Model Serialization: Joblib

---

## 📊 Input Parameters

* Area
* BHK
* Square Feet
* Bathroom
* Balcony
* Location

---

## 📸 Screenshots

(Add your project screenshots here)

---

## 🚀 Deployment

Deployed using **Render**

* Build Command:

```
pip install -r requirements.txt
```

* Start Command:

```
gunicorn house_price_app.app:app
```

---

## 👨‍💻 Author

**Kazi Sufiyan Mohsin**

* 🔗 LinkedIn: https://linkedin.com/in/kazisufiyan
* 💻 GitHub: https://github.com/kazisufiyan-k2

---

## ⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub!

---
