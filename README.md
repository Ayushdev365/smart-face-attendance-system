# 🎓 Smart Face Recognition Attendance System

An AI-powered attendance management system that uses real-time face recognition, liveness detection, and IP camera integration to automate attendance securely and accurately.

Built using **FastAPI**, **React**, **InsightFace**, **OpenCV**, and **SQLite**, this system supports both **RTSP IP cameras** and **laptop webcams**, making it suitable for classrooms, offices, laboratories, and institutions.

---

## 🚀 Features

### 👤 Face Recognition
- Real-time face detection
- High-accuracy face recognition using InsightFace
- Face embedding storage
- Multiple face detection
- Single-frame attendance recognition

### 🎥 Camera Support
- RTSP IP Camera support (Tapo C200)
- Laptop webcam support
- Camera source switching
- Automatic reconnection
- Real-time streaming

### 🛡️ Security
- Eye-blink liveness detection
- Head movement verification
- Anti-photo spoofing
- Duplicate attendance prevention
- Secure authentication

### 📊 Attendance Management
- Automatic attendance marking
- Entry & exit tracking
- Attendance history
- Daily reports
- Weekly reports
- Monthly reports
- Attendance percentage

### 👨‍🎓 Student Management
- Add students
- Update student information
- Face registration
- Face re-registration
- Student search
- Student management dashboard

### 📈 Analytics
- Dashboard statistics
- Attendance charts
- Present/Absent ratio
- Weekly trends
- Monthly analytics

### 📁 Export
- Excel (.xlsx)
- CSV
- Attendance reports
- Student reports

---

# 🏗️ Tech Stack

## Frontend
- React
- Vite
- Tailwind CSS
- Axios
- React Router

## Backend
- FastAPI
- Uvicorn
- WebSocket
- OpenCV
- InsightFace
- RetinaFace
- SQLite

## AI & Computer Vision
- InsightFace
- OpenCV
- RetinaFace
- NumPy
- SciPy

---

# 📂 Project Structure

```
smart-face-attendance-system/

├── backend/
│   ├── api/
│   ├── attendance/
│   ├── camera/
│   ├── database/
│   ├── detection/
│   ├── liveness/
│   ├── recognition/
│   ├── main.py
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── README.md
└── SETUP.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/smart-face-attendance-system.git

cd smart-face-attendance-system
```

---

## Backend

```bash
cd backend

python -m venv venv

source venv/bin/activate

pip install -r requirements.txt

python main.py
```

Backend

```
http://localhost:8000
```

API Documentation

```
http://localhost:8000/docs
```

---

## Frontend

```bash
cd frontend

npm install

npm run dev
```

Frontend

```
http://localhost:3000
```

---

# 🎥 Camera Support

Supports

- RTSP IP Cameras
- ONVIF Cameras
- Laptop Webcam

Example

```
rtsp://username:password@camera-ip:554/stream1
```

---

# 🔄 System Workflow

```
Camera
      │
      ▼
Face Detection
      │
      ▼
Face Recognition
      │
      ▼
Liveness Detection
      │
      ▼
Attendance Engine
      │
      ▼
Database
      │
      ▼
Dashboard & Reports
```

---

# 📊 Dashboard

- Live Camera Feed
- Student Management
- Attendance Logs
- Analytics
- Excel Export
- Reports

---

# 🔐 Security Features

- Liveness Detection
- Anti-Spoofing
- Secure Login
- Duplicate Prevention
- Session Validation

---

# 📸 Screenshots

> Add screenshots here

```
screenshots/

login.png

dashboard.png

camera.png

students.png

reports.png
```

---

# 🎥 Demo

> Add your demo video or GIF here.

---

# 🚀 Future Improvements

- Face Mask Recognition
- Cloud Database
- Docker Deployment
- Multi-Camera Support
- Multi-Classroom Support
- Mobile Application
- Email Notifications
- AI Attendance Analytics
- QR Code Backup Attendance
- Voice Notifications

---

# 🤝 Contributing

Pull requests are welcome.

For major changes, please open an issue first.

---

# 📜 License

MIT License

---

# 👨‍💻 Developer

**Ayush Chouksey**

Computer Science Engineering Student

AI | Computer Vision | Full Stack Developer

GitHub:
https://github.com/Ayushdev365

LinkedIn:
https://www.linkedin.com/in/ayushchouksey-dev365/

---

⭐ If you found this project useful, don't forget to Star the repository.
