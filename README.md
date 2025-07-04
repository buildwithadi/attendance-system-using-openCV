# 🎯 Face Recognition Attendance System

A Computer Vision-based project that automates attendance marking using real-time facial recognition. This system captures faces through a webcam, matches them with a trained dataset, and records attendance in an Excel file — eliminating the need for manual entry.

---

## 📌 Project Overview

Manually marking attendance can be time-consuming and error-prone. This project leverages **OpenCV** and **face recognition** libraries to identify individuals in real-time and logs their presence with a timestamp. It’s a lightweight, offline solution ideal for small institutions or classroom use.

---

## 🚀 Technologies & Tools Used

- **Language:** Python  
- **Libraries:**  
  - `OpenCV` – Image processing and camera handling  
  - `face_recognition` – Face detection and comparison  
  - `NumPy`, `Pandas` – Data handling  
  - `datetime`, `os` – File and time management  
- **Output File:** Excel/CSV-based attendance log
- 
---

## ⚙️ Features

✅ Real-time face detection via webcam  
✅ Identifies known faces from a training set  
✅ Logs name, date, and time in a `.csv` file  
✅ Avoids duplicate entries in the same session  
✅ Lightweight and fully offline  

---

## 🧪 How It Works

1. **Load Training Images** – All images in `ImagesAttendance/` are encoded.
2. **Capture Webcam Feed** – OpenCV captures real-time video frames.
3. **Face Matching** – The system matches faces against the encoded dataset.
4. **Log Attendance** – Upon a successful match, the system logs name, date, and time.

---

## 📊 Sample Output (CSV)

| Name     | Date       | Time     |
|----------|------------|----------|
| Aditya   | 2025-07-04 | 09:12:03 |
| Rohan    | 2025-07-04 | 09:14:10 |
