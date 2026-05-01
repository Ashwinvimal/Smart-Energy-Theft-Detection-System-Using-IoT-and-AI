# Smart-Energy-Theft-Detection-System-Using-IoT-and-AI
Smart Energy Theft Detection System using ESP32, IoT, and AI concepts. This project monitors real-time power consumption using a current sensor and detects electricity theft. It sends alerts via Blynk and Telegram and automatically cuts power using a relay when theft is detected.

# ⚡ Smart Energy Theft Detection System (IoT + ESP32)

This project is an IoT-based Smart Energy Theft Detection System that monitors real-time electricity consumption and detects abnormal usage patterns. It uses an ESP32 microcontroller, current sensor, and cloud integration to identify possible electricity theft and take immediate action.

---

## 🚀 Features

- 📡 Real-time energy monitoring using ESP32
- ⚡ Current sensing using analog sensor
- ☁️ Cloud integration via Blynk
- 🤖 Telegram alerts for theft detection
- 🔔 Buzzer alert system
- 🔌 Automatic power cut using relay
- 📊 Live voltage, current, and power display

---

## 🧠 How It Works

1. Current sensor measures real-time energy consumption  
2. ESP32 processes the data  
3. Data is sent to Blynk cloud for monitoring  
4. System checks for abnormal (low current) conditions  
5. If theft is detected:
   - Alert sent via Telegram  
   - Buzzer activated  
   - Power supply is cut using relay  

---

## 🛠️ Hardware Components

- ESP32 Microcontroller  
- Current Sensor (ACS712 or similar)  
- Relay Module  
- Buzzer  
- LCD Display (I2C)  
- Wi-Fi Connection  

---

## 💻 Software & Tools

- Arduino IDE  
- Blynk IoT Platform  
- Telegram Bot API  
- Embedded C (Arduino)  

---

## 📂 Code Overview

The system performs:

- Current measurement using ADC  
- Noise filtering and threshold detection  
- Theft detection logic based on low current duration  
- Cloud communication (Blynk)  
- Alert system (Telegram + buzzer)  
- Relay control for power cut  

📌 Main code file included in repository  
(Refer to uploaded code) :contentReference[oaicite:0]{index=0}  

---

## ⚠️ Theft Detection Logic

- If current drops below threshold for a certain time  
- System assumes bypass/theft condition  
- Triggers:
  - Alert notification  
  - Buzzer warning  
  - Power cut  

---

## 📱 Output

- LCD displays voltage and current  
- Blynk app shows live data  
- Telegram sends theft alert messages  
- Relay disconnects load  

---

## 🔒 Future Improvements

- AI-based anomaly detection  
- Mobile app dashboard  
- Cloud database integration  
- Smart grid scalability  

---

## 📌 Conclusion

This system provides a low-cost and efficient solution for detecting electricity theft using IoT technology. It ensures real-time monitoring, quick detection, and immediate action, making it suitable for smart energy systems.

---

## 👨‍💻 Author

- B R VIMAL AANANTH 

---

## ⭐ Give a Star

If you found this project useful, give it a ⭐ on GitHub!
