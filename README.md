# 🎓Attendance_Management_System_using_Face_Recognition  
> **Automating attendance with AI-powered face recognition using Python & OpenCV**

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg?style=for-the-badge" alt="Python Version"/>
  <img src="https://img.shields.io/badge/OpenCV-4.x-green.svg?style=for-the-badge" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="License"/>
  <img src="https://img.shields.io/badge/Status-Active-success.svg?style=for-the-badge" alt="Status"/>
</p>

<p align="center">
  <b>📸 Face Detection | 🧑‍💼 Real-time Recognition | 🗓️ Auto Attendance Logging</b>
</p>

---

## 📑 Table of Contents
- [📘 Overview](#-overview)
- [⚙️ Features](#️-features)
- [🏗️ Project Architecture](#️-project-architecture)
- [🧠 Tech Stack](#-tech-stack)
- [🔁 Workflow](#-workflow)
- [🖥️ Screenshots](#️-screenshots)
- [⚙️ Installation](#️-installation)
- [📂 Modules Description](#-modules-description)
- [📊 Sample Output](#-sample-output)
- [🚀 Future Enhancements](#-future-enhancements)
- [📚 References](#-references)
- [👨‍💻 Author](#-author)
- [🏁 Conclusion](#-conclusion)

---

## 📘 Overview

The **Attendance Management System using Face Recognition** is an **AI-powered application** that automates the attendance process by identifying faces in real time through a webcam.  
It replaces manual attendance tracking with a **secure, contactless, and efficient solution** powered by **Python and OpenCV**.

This project is designed for **schools, colleges, and organizations** that require accurate attendance tracking while minimizing human intervention.

## 🔁 How its Working?
[Working](https://github.com/AdarshVL/Attendence_management_system_using_face_recognition/blob/main/AICTE/README.md)

---

## ⚙️ Features

✅ **Real-Time Face Detection & Recognition** using Haar Cascade Classifier  
✅ **Automatic Attendance Marking** with name, ID, date, and time  
✅ **GUI Interface** built using Tkinter for ease of use  
✅ **Manual Attendance Option** for exceptional cases  
✅ **Training Module** to register new faces  
✅ **Attendance Record Display** with CSV export  
✅ **Lightweight & Offline Operation** – No Internet required  

---

## 🏗️ Project Architecture
```
Attendence_management_system_using_face_recognition/
│
├── attendance.py                  # GUI and attendance management
├── automaticAttedance.py          # Core face recognition and attendance logic
├── takeImage.py                   # Capture student images
├── trainImage.py                  # Train facial data using OpenCV
├── show_attendance.py             # Display attendance records
├── takemanually.py                # Manual attendance entry
│
├── StudentDetails/                # Stores student registration details
├── TrainingImage/                 # Raw captured images
├── TrainingImageLabel/            # Encoded training data
├── UI_Image/                      # App icons and screenshots
│
├── haarcascade_frontalface_default.xml  # Pretrained face detection model
├── AMS.ico                        # Application icon
├── project_requirement.txt        # Dependency file
├── README.md                      # Documentation
└── _config.yml                    # GitHub Pages config (optional)

```

## 🧠 Tech Stack

| Category | Technology |
|-----------|-------------|
| **Language** | Python 3.x |
| **Libraries** | OpenCV, Numpy, Pandas, Tkinter, datetime |
| **Face Detection** | Haar Cascade Classifier |
| **Storage** | CSV Files / Local Storage |
| **IDE/Tools** | VS Code / PyCharm |
| **Version Control** | Git & GitHub |

---

## 🔁 Workflow

```
graph TD
A[Student Registration] --> B[Capture Face Images]
B --> C[Train Facial Model]
C --> D[Real-time Recognition]
D --> E[Mark Attendance in CSV]
E --> F[View Attendance Records]

```

## 🖥️ Screenshots
 <img src="UI_Image/dashboard.png" width="600" alt="Dashboard Interface"/><br/>

## 📊 Sample Dashboard Interface
<img src="UI_Image/face_detection.png" width="600" alt="Face Detection"/><br/> 
Real-time Face Detection and Attendance Marking

## ⚙️ Installation

1️⃣ Clone the Repository
```
git clone https://github.com/AdarshVL/Attendence_management_system_using_face_recognition.git
cd Attendence_management_system_using_face_recognition
```
2️⃣ Install Dependencies
```
pip install -r project_requirement.txt
```
3️⃣ Run the Application
```
python automaticAttedance.py
```
## 📂 Modules Description

| File                                  | Description                                    |
| ------------------------------------- | ---------------------------------------------- |
| `takeImage.py`                        | Capture student face images using webcam       |
| `trainImage.py`                       | Train the recognition model                    |
| `automaticAttedance.py`               | Detect and recognize faces to mark attendance  |
| `attendance.py`                       | Main GUI-based attendance manager              |
| `show_attendance.py`                  | View attendance in tabular format              |
| `takemanually.py`                     | Add attendance manually when recognition fails |
| `haarcascade_frontalface_default.xml` | Pretrained classifier for face detection       |

## 📊 Sample Output
| Name            | ID  | Date       | Time     |
| --------------- | --- | ---------- | -------- |
| Adarsh Lilhare  | 101 | 2025-10-07 | 09:15:24 |
| Rishikesh Patil | 102 | 2025-10-07 | 09:16:10 |


## 📁 Stored as CSV:
 [Attendance](https://github.com/AdarshVL/Attendence_management_system_using_face_recognition/blob/main/AICTE/Attendance.xlsx) 


## 🚀 Future Enhancements

🔹 Integrate with MySQL or Firebase for centralized storage

🔹 Build an Admin Dashboard (React + Flask) for data visualization

🔹 Add QR Code verification as secondary authentication

🔹 Implement Email notifications for daily reports

🔹 Deploy on Cloud (AWS/GCP) for real-time scalability

## 📚 References

🔹 OpenCV Documentation

🔹 Python Tkinter GUI Docs

🔹 Face Detection with Haar Cascades

🔹 Real Python: Face Recognition

---
## 🏁 Conclusion

The Attendance Management System using Face Recognition revolutionizes the traditional attendance process by merging AI, Computer Vision, and Automation.
It’s a contactless, accurate, and scalable solution that enhances classroom or office productivity.

---

## 👨‍💻 Author

---
### Adarsh Lilhare 

🎓 B.Tech in Artificial Intelligence & Data Science

💼 AI & Data Science Student | 💻 Developer | 🌍 Open Source Contributor | 🚀 Computer Vision Enthusiast

📧 [Email](adarshlilhare@example.com)

🐙 [GitHub](https://github.com/AdarshVL) 

🌐 [Portfolio](https://adarshlilhare.dev)

🔗 [LinkedIn](https://www.linkedin.com/in/adarsh-lilhare-b98a91290/)

---
