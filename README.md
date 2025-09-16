# 🩺 Smart Healthcare Monitoring System (IoT + ML)

## 📌 Overview
This project is a **Smart IoT-based Healthcare Monitoring System** that collects health data (Temperature, Heart Rate, SpO2) using sensors and applies **Machine Learning** to predict anomalies.  
The system can send real-time data to a **cloud dashboard** for monitoring.

---

## 🛠️ Tech Stack
- **Hardware:** Arduino/ESP32, DHT11 (Temperature), Pulse Sensor, SpO2 Sensor
- **Cloud:** Firebase / Thingspeak
- **ML:** Python, Pandas, Scikit-learn, TensorFlow
- **Dashboard:** Blynk/Firebase web app

---

## ⚙️ Setup Instructions

### 🔹 Hardware
1. Connect sensors to Arduino/ESP32
2. Upload `arduino_code.ino` (provided in `hardware/`)
3. Connect to WiFi for cloud update

### 🔹 ML Model
1. Install requirements:  
   ```bash
   pip install -r requirements.txt
