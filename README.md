# 🩺 HypoSense AI – AI-Powered Hypoglycemia Risk Detection

An AI-powered web application that estimates the risk of hypoglycemia using non-invasive physiological signals, machine learning, and Generative AI.

## 🚀 Features

- 📷 Real-time webcam-based monitoring
- ❤️ Pulse rate estimation
- 👁️ Blink rate detection using facial landmarks
- 🧠 Machine Learning-based hypoglycemia risk prediction
- 🤖 Gemini AI-powered health explanation
- 📄 Medical report image upload and AI analysis
- 🍽️ Meal gap tracking
- 💉 Insulin usage input
- 🩸 Last glucose reading input
- 👤 Age input
- 💬 Interactive AI chatbot
- 📊 Risk classification (LOW / MEDIUM / HIGH)

---

# 🏗️ System Architecture

```
Webcam
   │
   ▼
Pulse & Blink Detection
   │
   ▼
User Inputs
(Age, Glucose, Meal Gap, Symptoms)
   │
   ▼
Machine Learning Model
(Random Forest Classifier)
   │
   ▼
Risk Prediction
   │
   ▼
Gemini AI
   │
   ▼
Personalized Explanation & Recommendations
```

---

# 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript
- MediaPipe FaceMesh

### Backend
- Python
- Flask

### Machine Learning
- Scikit-Learn
- Random Forest Classifier
- Pandas
- NumPy

### Generative AI
- Google Gemini API

### Computer Vision
- OpenCV
- MediaPipe

---

# 📂 Project Structure

```
HypoSense-AI/
│
├── app.py
├── train_risk.py
├── model.pkl
├── diabetes.csv
├── updated_data.csv
├── hypoglycemia-screen.html
├── requirements.txt
├── README.md
└── static/
```

---

# 📈 Machine Learning

The model was trained using a combination of:

- Pima Indians Diabetes Dataset
- Synthetic physiological data

Additional generated features:

- Pulse Rate
- Blink Rate
- Hours Since Meal
- Sweating
- Dizziness

Model Used:

- Random Forest Classifier

Performance:

- Accuracy: **96%**
- Risk Classes:
  - LOW
  - MEDIUM
  - HIGH

---

# 🤖 Generative AI

Gemini AI is used to:

- Explain the prediction
- Summarize physiological readings
- Suggest preventive actions
- Analyze uploaded medical reports
- Answer health-related questions

---

# 📊 Inputs

The application considers:

- Age
- Last Blood Glucose Reading
- Pulse Rate
- Blink Rate
- Meal Gap
- Symptoms
- Insulin Context

---

# 📤 Outputs

The system predicts:

- LOW Risk
- MEDIUM Risk
- HIGH Risk

Along with:

- AI Explanation
- Suggested Actions
- Health Summary

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/HypoSense-AI.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

Open

```
http://127.0.0.1:5000
```

---

# 📸 Future Improvements

- Wearable sensor integration
- Continuous glucose monitor (CGM) support
- Cloud database
- User authentication
- Health history dashboard
- Mobile application
- Explainable AI dashboard

---

# ⚠️ Disclaimer

This application is designed for educational and research purposes only.

It is **not intended to diagnose, treat, or replace professional medical advice**. Always consult a qualified healthcare professional for medical decisions.

---

# 👨‍💻 Author

**Chirag Garg**

B.E. Computer Science & Engineering

BMS Institute of Technology & Management

---

## ⭐ If you like this project, don't forget to Star the repository!
