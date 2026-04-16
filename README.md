# 🏥 AI-Based Medical Pre-Diagnosis System

A full-stack web application that predicts possible diseases from user-entered symptoms using Machine Learning and NLP techniques. The system provides confidence scores, severity levels, medical advice, and top-3 alternative predictions.

---

## 🚀 Live Demo

👉 (Add your Render link here after deployment)

---

## 🎯 Problem Statement

Many people delay medical consultation or panic unnecessarily due to lack of basic symptom understanding. This system provides an initial AI-based assessment to guide users.

---

## 💡 Features

* 🧠 Symptom input using natural language (TF-IDF)
* 🤖 Machine Learning models (Decision Tree & Random Forest)
* 📊 Disease prediction with confidence score
* ⚠️ Severity classification (Low / Medium / High)
* 💊 Basic medical advice
* 🔝 Top-3 alternative predictions
* 🎤 Voice input support
* 🌗 Multi-theme UI (Dark/Light mode)
* 🕘 Local history tracking
* ❤️ Health check endpoint (`/health`)

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Flask (Python)
* **Machine Learning:** Scikit-learn
* **NLP:** TF-IDF Vectorization
* **Deployment:** Render / Railway

---

## 📂 Project Structure

```
project/
│── app.py
│── model/
│   ├── train_model.py
│   ├── model.pkl
│── templates/
│── static/
│── dataset/
│── requirements.txt
│── Procfile
│── render.yaml
```

---

## ⚙️ Local Setup

```bash
cd project
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python model/train_model.py
python app.py
```

Open 👉 http://127.0.0.1:5000

---

## 🌐 Deployment

### 🔹 Render (Recommended)

* Push code to GitHub
* Create **New → Blueprint**
* Select repo → auto-deploy

### 🔹 Manual Setup

Build:

```
pip install -r requirements.txt && python model/train_model.py
```

Start:

```
gunicorn app:app --workers 2 --threads 4 --timeout 120
```

---

## 🔐 Environment Variables

```
PORT=5000
FLASK_DEBUG=false
```

---

## 🧪 Model Details

* Compared:

  * Decision Tree
  * Random Forest
* Selected Random Forest for better accuracy and generalization
* Preprocessing using TF-IDF for symptom text

---

## 📌 Future Improvements

* 📱 Mobile app version
* 🧠 Deep Learning (LSTM / BERT)
* 🏥 Integration with real hospital APIs
* 🌍 Multi-language support

---

## ⚠️ Disclaimer

This system is for educational purposes only and not a substitute for professional medical advice.

---

## 👨‍💻 Author

Mallikarjun Kudalli
