# 🚗 SecurePark AI

A smart and secure parking management system powered by **ANPR (Automatic Number Plate Recognition)**, motion detection, and intelligent access control. Designed to streamline parking lot operations while enhancing surveillance, SecurePark AI automates vehicle recognition, slot assignment, access differentiation (VIP/Guest), and live monitoring.

---

## 🧠 Overview

**SecurePark AI** is an integrated pre-development prototype that combines **parking management** with **AI-powered surveillance tools**. Utilizing image processing, real-time video feeds, and number plate recognition, the system can detect incoming and outgoing vehicles, assign parking spots dynamically, and manage access levels efficiently.

It provides a seamless experience for vehicle owners and powerful oversight tools for parking administrators. By combining **automation, security, and smart data logging**, the system helps reduce human intervention, enhance surveillance, and improve parking efficiency.

---

## 🎯 Key Features

### 🔍 Detection & Surveillance
- **ANPR System (Automatic Number Plate Recognition)**: Automatically detects and reads license plates of vehicles using CCTV/IP cameras.
- **Motion Detection**: Detects incoming and outgoing vehicles in real-time.
- **Video Surveillance Integration**: Connects with security/IP cameras to monitor vehicle movement and record footage.

### 🅿️ Parking Management
- **Auto Slot Assignment**: Assigns parking lot numbers automatically for incoming vehicles.
- **Parking Slot Sorting**: Smart slot sorting for optimized space usage.
- **Real-Time Availability Display**: Shows live slot availability for admin and optionally users.

### 🎖️ Access Control
- **VIP/Guest Modes**: Allows different access levels for users (e.g., employees, visitors, VIPs).
- **Member Hierarchy**: Assigns slots based on user level or permission.
- **Unauthorized Vehicle Alerts**: Notifies admins when a non-recognized vehicle is detected.

### 🔔 Notifications & Alerts
- **Real-Time Alerts**: System can notify admins or users about slot assignments, unauthorized access, or overstayed vehicles.
- **Stolen Vehicle Monitoring**: Cross-reference license plates with a watchlist for flagged or stolen vehicles.

---

## 🧰 Technologies Used

| Component            | Tech/Tools                                 |
|----------------------|---------------------------------------------|
| **Frontend**         | python tkinter framework         |
| **Backend**          | Python, OpenCV, Flask/Django (dev stage)   |
| **Image Processing** | OpenCV, NumPy                              |
| **Video Input**      | CCTV / IP Cameras                          |
| **Storage**          | psql / Local DB (Prototype)              |
| **Optional**         | Telegram API for notifications             |

---

## 🖼️ Screenshots

![Home](https://github.com/user-attachments/assets/938d732b-0eab-4fdb-b6fe-449f97c520c9)
![Telegram Notification](https://github.com/user-attachments/assets/2c001e59-d302-4674-888e-3240c670ce3f)


