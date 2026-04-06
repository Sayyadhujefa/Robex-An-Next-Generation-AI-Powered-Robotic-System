<p align="center">
  <img src="banner.png" alt="ROBEX Banner" width="100%" />
</p>
# 🤖 ROBEX – IoT Based Robot Powered by LLM

## 📌 Overview
ROBEX is an AI-powered IoT robotic assistant designed for automated attendance management using face recognition, liveness detection, and voice-based interaction.

## 🚀 Features
- Face Detection (Haar Cascade)
- Face Recognition (LBPH + FaceNet)
- Liveness Detection (EAR)
- Anti-Spoofing (YOLOv8)
- Voice Control using LLM
- ESP32 Robot Control
- Automated Attendance (Google Sheets)
- GUI Interface

## 🧠 Tech Stack
- Python, OpenCV, Flask
- ESP32, ESP32-CAM
- SQLite, Google Sheets API
- HTML, CSS, JS

## ⚙️ Installation

### 1. Clone Repo
```bash
git clone https://github.com/yourusername/robex.git
cd robex
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run Backend
```bash
python backend/app.py
```

### 4. Open Frontend
Open `frontend/index.html` in browser

---

## 🤖 Hardware Setup
- Connect ESP32 with motors
- Upload Arduino code from `/hardware`
- Ensure WiFi connectivity

---

## 📊 Workflow
1. Capture video using ESP32-CAM
2. Detect & recognize face
3. Verify liveness
4. Mark attendance in database & cloud
5. Control robot via voice commands

---

## 📈 Results
- High accuracy recognition
- Real-time response
- Secure attendance logging

---

## 🔮 Future Improvements
- Mobile App Integration
- Multi-user voice interaction
- Cloud AI deployment

---

## 👨‍💻 Authors
- Sayyad Hujefa Ayub
- Team ROBEX

---

## 📜 License
MIT License
