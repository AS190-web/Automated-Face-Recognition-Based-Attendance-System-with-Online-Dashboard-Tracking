# 👁️ Smart Biometric Face Recognition Tracker

## 📌 Project Overview

The **Smart Biometric Face Recognition Tracker** is an offline computer vision–based application designed to automate attendance tracking using **facial recognition technology**.

The system captures live video from a **webcam**, detects faces in real time, recognizes registered individuals, and automatically records their attendance in both **CSV files** and a **MySQL database**.

This project is developed using **Python and OpenCV** and provides a **contactless, secure, and efficient attendance solution** suitable for schools, colleges, and organizations.

---

# 🎯 Objectives

- Eliminate **manual attendance systems**
- Prevent **proxy attendance**
- Provide a **contactless biometric attendance solution**
- Ensure **accurate identity verification** using facial features
- Store attendance records **digitally for analysis**
- Operate completely **offline without internet dependency**

---

# 🛠 Technologies Used

| Component | Technology |
|----------|-------------|
| Programming Language | Python 3.10.11 |
| Computer Vision | OpenCV |
| Numerical Processing | NumPy |
| Database | MySQL |
| Database Connector | MySQL Connector |
| Face Detection | Haar Cascade Classifier |
| Face Recognition | LBPH (Local Binary Pattern Histogram) |
| Platform | Windows OS |
| Hardware | Webcam |

---

# ⚙️ System Workflow

1️⃣ Capture face images of users and create dataset  
2️⃣ Train the LBPH face recognition model  
3️⃣ Detect faces using **Haar Cascade classifier**  
4️⃣ Recognize faces using **LBPH algorithm**  
5️⃣ Mark attendance automatically  
6️⃣ Store attendance records in **CSV and MySQL database**

---

# 📂 Project Structure

Smart-Biometric-Face-Recognition-Tracker/

│
├── Code/
│ ├── Code1.py
│ ├── Code2.py
│ ├── Code3.py
│ ├── Code4.py
│ └── mysql_test.py
│
├── Data Sets and Samples/
│ ├── dataset/
│ ├── Outputs/
│ └── haarcascade_frontalface_default.xml
│
├── README.md
├── LICENSE
└── .gitignore


---

# 🚀 How to Run the Project

### Step 1: Install Required Libraries

pip install opencv-python numpy mysql-connector-python

### Step 2: Setup MySQL Database

Create a database for storing attendance records.

Example: CREATE DATABASE attendance_system;

### Step 3: Run the Modules

1. Capture face dataset
2. Train the model
3. Start live face recognition

Example: python Code4.py

# 📊 Output

The system generates:

- **Real-time face recognition through webcam**
- **Attendance stored in CSV file**
- **Attendance stored in MySQL database**
- **Face detection and recognition outputs**

Sample output images are stored in:

---

# 🔒 Features

✔ Real-time face recognition  
✔ Automated attendance tracking  
✔ Offline system (no internet required)  
✔ Secure biometric identification  
✔ CSV + Database attendance storage

---

# 📎 Disclaimer

This project is intended for **educational and research purposes only**.




