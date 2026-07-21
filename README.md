# 🧩 AutiGuard – Smart Wearable Safety System for Children with Autism

AutiGuard is an IoT-based wearable safety device developed to assist children with Autism Spectrum Disorder (ASD). The system continuously monitors the child's health and location while providing emergency communication features for parents and caregivers.

The wearable integrates multiple sensors to monitor heart rate, blood oxygen level, body movement, and geographical location. In emergency situations, the device automatically transmits the child's live location to guardians, enabling quick assistance and improving overall safety.

---

# 📌 Project Objectives

- Monitor the child's vital signs in real time.
- Track the child's location using GPS.
- Detect abnormal movement or emergency situations.
- Provide instant location sharing with caregivers.
- Improve the safety and independence of autistic children.

---

# ✨ Features

- ❤️ Real-time Heart Rate Monitoring
- 🩸 Blood Oxygen (SpO₂) Monitoring
- 📍 GPS Live Location Tracking
- 🚶 Motion Detection using Accelerometer
- 📡 GSM Communication for Emergency Alerts
- 📱 IoT-based Remote Monitoring
- 🔋 Low Power Wearable Design
- 🚨 Emergency Location Sharing

---

# 🛠 Hardware Components

- ESP32 Development Board
- MAX30100 Pulse Oximeter Sensor
- MPU6050 Accelerometer & Gyroscope
- NEO-6M GPS Module
- SIM800L GSM Module
- Rechargeable Li-ion Battery
- OLED Display (Optional)
- Push Button for Emergency Trigger

---

# 💻 Software Used

- Arduino IDE
- Embedded C/C++
- TinyGPS++ Library
- Wire Library
- WiFi Library

---

# ⚙️ Working Principle

1. ESP32 continuously collects sensor data.
2. MAX30100 measures heart rate and blood oxygen level.
3. MPU6050 monitors body movement and detects unusual motion.
4. GPS module acquires the child's live location.
5. In case of emergency, the SIM800L module sends the live location to parents or caregivers.
6. Parents can monitor the child's condition remotely.

---

# 📂 Project Structure

```
AutiGuard/
│
├── Arduino_Code/
├── Circuit_Diagram/
├── Images/
├── Documentation/
├── README.md
└── LICENSE
```

---

# 🔧 Hardware Connections

| Component | ESP32 Pin |
|-----------|-----------|
| MAX30100 | I2C (SDA, SCL) |
| MPU6050 | I2C (SDA, SCL) |
| NEO-6M GPS | UART RX/TX |
| SIM800L GSM | UART RX/TX |
| Push Button | GPIO |

---

# 📊 Applications

- Autism Care
- Child Safety Monitoring
- Special Education Schools
- Hospitals
- Rehabilitation Centers
- Elderly Monitoring
- Personal Healthcare

---

# ✅ Advantages

- Portable wearable device
- Real-time health monitoring
- Live GPS tracking
- Emergency communication
- Low-cost implementation
- Easy to operate
- Suitable for daily use

---

# 🚀 Future Enhancements

- AI-based behavior prediction
- Fall detection algorithm
- Indoor positioning system
- Mobile application
- Cloud database integration
- Voice assistant support
- Machine learning for behavioral analysis
- Wi-Fi and Bluetooth synchronization

---

# 🧠 Skills Demonstrated

- Embedded Systems
- Internet of Things (IoT)
- ESP32 Programming
- GPS Tracking
- GSM Communication
- Sensor Interfacing
- Healthcare Wearable Design
- Real-Time Monitoring
- Arduino Programming

---

# 📸 Project Images

Add the following images to improve your repository:

- Device Prototype
- Circuit Diagram
- Hardware Setup
- Sensor Connections
- Working Demonstration
- Final Wearable Prototype

---

# 📈 Project Outcome

This project demonstrates the integration of IoT, embedded systems, and healthcare technologies to develop a smart wearable device that enhances the safety and well-being of children with Autism Spectrum Disorder. The system provides continuous monitoring and emergency communication, making it suitable for real-world assistive healthcare applications.

---

# 👨‍💻 Author

**Mukesh M**

B.Tech – Electronics and Communication Engineering

Sri Manakula Vinayagar Engineering College

📧 Email: mukeshmuniraj2005@gmail.com

🔗 GitHub: https://github.com/Mukesh02-tech

🔗 LinkedIn: https://www.linkedin.com/in/mukeshmuniraj05

---

## ⭐ If you found this project useful, consider giving it a Star!
