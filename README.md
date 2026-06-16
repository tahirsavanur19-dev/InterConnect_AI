# InterConnect_AI

## 📌 Project Overview

InterConnect AI is an AI-powered communication and accessibility platform designed to bridge communication gaps using Speech Processing, Language Translation, and Sign Language Recognition technologies.

The system integrates Speech-to-Text (STT), Text-to-Speech (TTS), multilingual translation, and AI-based Sign Language Recognition into a single platform. It aims to improve communication accessibility for users across different languages and communication methods.

---

## ⚙️ Tech Stack

* Python
* FastAPI
* React.js
* JavaScript
* TensorFlow / Keras
* OpenCV
* CvZone
* SpeechRecognition
* pyttsx3
* Google Translate API (googletrans)
* PyEnchant
* Tkinter
* PIL (Pillow)

---

## 🚀 Features

* Text-to-Speech (TTS) Conversion
* Speech-to-Text (STT) Recognition
* Multilingual Text Translation
* Speech-to-Translation Workflow
* Translation-to-Speech Output
* AI-based Sign Language Recognition
* Hand Landmark Detection
* CNN-based Gesture Classification
* Word Prediction & Suggestions
* FastAPI REST API Integration
* React-based User Interface

---

## 🧠 System Workflow

### Communication Module

1. User enters text or speech input
2. Speech is converted into text using STT
3. Text is translated into the selected language
4. Translated content can be converted back into speech
5. Output is presented to the user

### Sign Language Module

1. Webcam captures hand gestures
2. OpenCV detects hand landmarks
3. CNN model classifies gestures
4. Predicted gestures are converted into text
5. Suggested words are generated
6. Final output can be spoken using TTS

---

## 🛠️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/tahirsavanur19-dev/InterConnect_AI 
```

### 2. Move into project folder

```bash
cd InterConnect_AI
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run FastAPI Backend

```bash
uvicorn main:app --reload
```

### 5. Run React Frontend

```bash
npm install
npm run
```

### 6. Open in Browser

```text
http://localhost:3000
```

---

## 📂 Project Structure

```text
InterConnect_AI/
│
├── backend/
│   ├── main.py
│   ├── translation_module.py
│   ├── requirements.txt
│   ├── sign_language_module/
│       ├── final_pred.py
│       ├── cnn8grps_rad1_model.h5
├── frontend/
│   ├── src/
│   │   ├── App.js
│   │   ├── DataFetcher.js
│   │   └── App.css
│
├── sign_language_module/
│   ├── final_pred.py
│   ├── cnn8grps_rad1_model.h5
│
├── assets/
├── README.md
```

---

## 📊 Supported Languages

* English
* Hindi
* Marathi
* Urdu
* Spanish
* French
* German
* Chinese
* Japanese
* Arabic
* Portuguese

---

## 🔮 Future Improvements

* Full Web Integration of Sign Language Module
* Real-time Video Communication
* AI Chatbot Integration
* Mobile Application Development
* Cloud Deployment
* Advanced Sentence-Level Sign Recognition
* User Authentication & Profiles

---

## 📌 Project Status

🚧 In Progress

Completed Modules:

* FastAPI Backend
* React Frontend
* Text-to-Speech
* Speech-to-Text
* Multilingual Translation
* Translation Speech Output
* Sign Language Recognition Prototype

Pending:

* Full Integration of Sign Language Module with Web Interface
* Deployment & Optimization


⚠️ This repository is temporarily unavailable due to technical issues during project migration and file organization.

---

## 📌 Note

This project is developed for educational and research purposes and demonstrates the integration of Artificial Intelligence, Computer Vision, Speech Processing, and Natural Language Processing to build an accessibility-focused communication platform.

---

## 👨‍💻 Author

**Tahirhussain Mahabub Savanur**

B.Sc. Data Science
