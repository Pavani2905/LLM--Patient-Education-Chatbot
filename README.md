# 🩺 Health Assist AI – LLM--Patient-Education-Chatbot

An AI-powered healthcare assistant designed to provide personalized patient education, disease prediction, prescription analysis, and doctor consultation support using Large Language Models (LLMs), Machine Learning, NLP, and OCR technologies.

## 📌 Project Overview

Health Assist AI is a smart healthcare web application that helps users:

- Predict diseases based on symptoms
- Analyze prescriptions using OCR
- Chat with an AI medical assistant
- Find nearby hospitals and pharmacies
- Book doctor appointments
- Connect with doctors via WhatsApp or video calls
- Maintain digital patient profiles

This project was developed as a B.Tech AIML major project.

---

## 🚀 Features

### 🤖 AI Medical Chatbot
- Real-time chatbot interaction
- Personalized healthcare responses
- NLP-based query understanding

### 🩺 Disease Prediction
- Predicts diseases using symptoms
- Uses Random Forest & SVM models
- Displays confidence scores

### 📄 Prescription Scanner
- OCR-based medicine extraction
- Detects dosage and medicine names
- Helps users understand prescriptions

### 📍 Nearby Medical Services
- Locate nearby:
  - Hospitals
  - Clinics
  - Pharmacies
- Google Maps API integration

### 📅 Appointment Booking
- Book doctor appointments online
- Appointment reminder support

### 👤 Patient Profile Management
- Stores patient history
- Maintains health records securely

### 💬 Doctor Consultation
- WhatsApp integration
- Video consultation support

### ⭐ Feedback System
- Star-based feedback and bug reporting system

---

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- JavaScript
- React.js
- Vite

### Backend
- Flask
- PHP

### Database
- MySQL / PostgreSQL

### AI & ML
- Python
- Scikit-learn
- TensorFlow
- Keras
- NLP
- Random Forest
- SVM

### OCR & Image Processing
- OpenCV
- Tesseract OCR

### APIs & Tools
- Google Maps API
- WhatsApp Integration
- WebRTC / Zoom API

---

## 📂 Project Structure

```bash
HealthAssistAI/
│
├── frontend/
│   ├── index.html
│   ├── login.html
│   ├── about.html
│   ├── appointment.html
│   ├── feedback.html
│   ├── profile.html
│   └── styles.css
│
├── backend/
│   ├── connect.php
│   ├── register.php
│   ├── save_profile.php
│   ├── feedback_handler.php
│   ├── store_appointment.php
│   └── pharmacy.js
│
├── models/
│   ├── disease_prediction_model.pkl
│   └── chatbot_model.pkl
│
├── dataset/
│   └── symptom_disease_dataset.csv
│
├── screenshots/
│
└── README.md


4️⃣ Open Frontend

Run frontend using Vite or open HTML files directly.# ⚙️ Installation

### 1️⃣ Clone Repository
bash
git clone https://github.com/your-username/health-assist-ai.git
cd health-assist-ai


### 2️⃣ Install Dependencies
bash
pip install -r requirements.txt


### 3️⃣ Run Flask Server
bash
python app.py

###4️⃣ Open Frontend
Run frontend using Vite or open HTML files directly.

📊 Machine Learning Model
Algorithms Used
Random Forest
Support Vector Machine (SVM)
Naive Bayes
Model Performance
Model	Accuracy
Random Forest	92%
OCR Extraction	85%
Chatbot Relevance	88%
