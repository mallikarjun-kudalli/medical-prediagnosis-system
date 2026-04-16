# 🏥 AI-Based Medical Pre-Diagnosis System

A full-stack web application that predicts possible diseases from user-entered symptoms using Machine Learning and NLP. The system provides confidence scores, severity levels, medical advice, and top-3 alternative predictions.

---

## 🎯 Problem Statement

Many people either ignore symptoms or panic unnecessarily due to lack of basic medical awareness. This project provides an AI-based preliminary diagnosis to guide users before consulting a doctor.

---

## 💡 Features

* 🧠 Natural language symptom input (TF-IDF)
* 🤖 Machine Learning models (Decision Tree & Random Forest)
* 📊 Disease prediction with confidence score
* ⚠️ Severity classification (Low / Medium / High)
* 💊 Basic advice (rest / consult doctor / emergency)
* 🔝 Top-3 disease predictions
* 🎤 Voice input support
* 🎨 Multiple UI themes
* 🕘 Local history tracking
* ❤️ Health check endpoint (`/health`)

---

## 📸 Screenshots

### 🏠 Home Page
![Home](screenshots/home.png)

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Flask (Python)
* **Machine Learning:** Scikit-learn
* **NLP:** TF-IDF Vectorization
* **Deployment:** Render / Railway

---

## 📂 Project Structure

```bash
medical-prediagnosis-system/
│── app.py
│── model/
│   ├── train_model.py
│   ├── medical_model.pkl
│   ├── model_metrics.json
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
git clone https://github.com/mallikarjun-kudalli/medical-prediagnosis-system.git
cd medical-prediagnosis-system
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python model/train_model.py
python app.py
```

Open 👉 http://127.0.0.1:5000

---

## 🧪 Model Details

* Compared:
  * Decision Tree
  * Random Forest
* Selected Random Forest for better accuracy and generalization.
* Used TF-IDF for text feature extraction.

---

## 📌 Future Improvements

* 📱 Mobile app version
* 🧠 Deep learning (LSTM / BERT)
* 🌍 Multi-language support
* 🏥 Integration with real hospital APIs

---

## ⚠️ Disclaimer

This system is for educational purposes only and not a substitute for professional medical advice.

---

## 👨‍💻 Author

Mallikarjun Kudalli
