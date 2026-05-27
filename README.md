# IoT-Based-Real-Time-Motor-Health-Monitoring-and-Insulation-Failure-Prediction-System
IoT-Based Real-Time Motor Health Monitoring and Insulation Failure Prediction System uses ESP32 with vibration, temperature, and current sensors to monitor motor condition. Data is sent to the cloud and analyzed using ML, with a Streamlit dashboard and email alerts for early fault detection.

## 🎯 Objectives
- Monitor motor parameters in real-time  
- Detect abnormal conditions early  
- Predict insulation and bearing failures  
- Provide alerts for preventive maintenance  
- Improve system reliability  

---

## ⚙️ System Architecture
Sensors → ESP32 → Firebase → Streamlit Dashboard → ML Model → Alerts


---

## 🧰 Hardware Components
- ESP32 Microcontroller  
- MPU6050 (Vibration Sensor)  
- DS18B20 (Temperature Sensor)  
- ACS712 (Current Sensor)  
- Relay Module (optional)  

---

## 💻 Software & Tools
- Python  
- Streamlit  
- Blynk IoT Platform  
- Firebase Realtime Database  
- Scikit-learn  
- Plotly  
- ReportLab  

---

## 🔍 Features
- Real-time monitoring  
- Machine learning-based prediction  
- Interactive dashboard  
- Trend analysis  
- Email alert with PDF report  
- Cloud storage (Firebase)  
- CSV data backup  

---

## 📊 Dashboard Functionalities
- Live Temperature, Vibration, Current display  
- Vibration Analysis chart  
- Current Analysis chart  
- Thermal trend visualization  
- Health Index display  
- Fault status indicators  

---

## 🤖 Machine Learning
- Input: Temperature, Vibration, Current  
- Output:
  - Insulation Status  
  - Bearing Status  

---

## 🚨 Alert System
- Email alert when:
  - Temperature exceeds limit  
  - Vibration increases  
  - Current overload detected  
- Includes PDF report attachment  

---

## 📁 Project Structure
├── app.py                # Streamlit dashboard

├── predict.py            # ML prediction logic

├── train_model.py        # Model training

├── blynk_fetch.py        # Sensor data fetching

├── email_alert.py        # Email notification system

├── model.pkl             # Trained ML model

├── scaler.pkl            # Data scaler

├── requirements.txt      # Dependencies

├── README.md             # Project documentation

└── sensor_data.csv       # Data storage

## ▶️ How to Run

pip install -r requirements.txt
streamlit run app.py
