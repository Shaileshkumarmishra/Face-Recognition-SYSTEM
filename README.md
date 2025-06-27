# Face-Recognition-SYSTEM

📌 **Project Overview (Summary)**  
This project is a **Face Recognition Attendance System** that automates attendance by capturing and recognizing faces through a camera. It records data in a **MySQL database** and is integrated with an **Android app** for easy user interaction, making it ideal for educational institutions and workplaces.

---

## 🔗 Industry Reference

**FA6 Class by Face-Six** – A commercial, classroom-focused face-recognition attendance solution.  
- **Website:** [attendance-face-recognition-sk-6c9f47.webflow.io](https://attendance-face-recognition-sk-6c9f47.webflow.io/)  
- **Key Highlights:**  
  - Up to **99% accuracy** and sub-1-second identification  
  - Real-time notifications & detailed attendance reports  
  - Deployable at entrances or inside classrooms  
  - Supports students, teachers, parents, and flagged “suspects”  
- **Use Case Fit:** Demonstrates how an end-to-end product addresses deployment ease, speed, and reporting—valuable benchmarks for our own system.
  ----

## 📸 Project Screenshots

### 🔹 Android App UI
![Android App](assets/android_ui.png)

### 🔹 Face Detection Example
![Face Detection](assets/face_detection.png)

### 🔹 Attendance Success Message
![Attendance Marked](assets/attendance_success.png)



---

## 🔍 Features
- 🎥 Real-time face detection and recognition using OpenCV
- 📸 Camera-based image capture
- 🗃️ Stores attendance data in a MySQL database
- 📱 Android app integration for:
  - Student registration (name, photo, roll number, DOB)
  - Face scan to mark attendance
- ⏱️ Marks attendance with date and time
- 🔁 Automatically resets for next scan

---

## ⚙️ Technologies Used
- Python (backend)
- OpenCV (image processing & face recognition)
- MySQL (database)
- Android Studio (mobile app)
- Flask or FastAPI (optional backend communication)
- MySQL Connector (Python-MySQL interaction)

---

## 🧪 How It Works
1. A student registers through the Android app with their photo and details.
2. Image and data are stored in the MySQL database using a Python backend.
3. During attendance, the app captures the student’s face and sends it to the Python script.
4. The system compares the captured face with stored faces.
5. If matched, attendance is marked and stored in the database.
6. The app displays confirmation and prepares for the next scan.

---

## ✅ Use Cases
- Schools & Colleges
- Offices & Workplaces
- Training Centers

---

## 🚀 Future Enhancements
- Add liveness detection to prevent spoofing
- Admin dashboard with attendance analytics
- Cloud-based storage support
- SMS/Email alerts for absentees

---

## 🛡️ License
This project is open-source under the **MIT License**. You are free to use, modify, and distribute it with attribution.

---

## 📂 Folder Structure (Example)
/face-recognition-system
│
├── /android-app # Android Studio project
├── /python-backend # Python scripts (face recognition, DB connector)
├── /model # Trained model and datasets
├── /assets # Images/screenshots for documentation
├── requirements.txt # Python dependencies
└── README.md # Project documentation
