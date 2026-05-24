# IoT-Based-Real-Time-Motor-Health-Monitoring-and-Insulation-Failure-Prediction-System
IoT-Based Real-Time Motor Health Monitoring and Insulation Failure Prediction System uses ESP32 with vibration, temperature, and current sensors to monitor motor condition. Data is sent to the cloud and analyzed using ML, with a Streamlit dashboard and email alerts for early fault detection.

🎯 Objectives
Monitor motor parameters in real-time
Detect abnormal conditions early
Predict insulation and bearing failures
Provide alerts for preventive maintenance
Improve system reliability and efficiency
⚙️ System Architecture
Sensors → ESP32 → Blynk Cloud → Streamlit Dashboard → ML Model → Alerts
🧰 Hardware Components
ESP32 Microcontroller
MPU6050 (Vibration Sensor)
DS18B20 (Temperature Sensor)
ACS712 (Current Sensor)
Relay Module (optional for protection)
💻 Software & Tools
Python
Streamlit
Blynk IoT Platform
Firebase Realtime Database
Scikit-learn (ML Model)
Plotly (Visualization)
ReportLab (PDF generation)
🔍 Features
📡 Real-time sensor data monitoring
📊 Interactive dashboard visualization
🤖 Machine learning-based fault prediction
📈 Trend analysis (rolling averages)
📧 Email alert with PDF report
☁ Cloud storage using Firebase
💾 Local CSV data backup
🔄 Auto-refresh system
📊 Dashboard Functionalities
Live Temperature, Vibration, Current display
Separate charts for:
Vibration Analysis
Current Analysis
Thermal Trends
Health Index visualization
Fault status indicators
🤖 Machine Learning
Model trained using real + simulated data
Features:
Temperature
Vibration
Current
Outputs:
Insulation Status
Bearing Status
🚨 Alert System
Sends email alerts when:
Temperature exceeds threshold
Vibration increases abnormally
Current overload detected
Includes PDF report attachment with analysis charts
