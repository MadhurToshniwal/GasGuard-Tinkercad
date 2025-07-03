# 🚨 GasGuard – Fire & Gas Detection System using Arduino (Tinkercad)

**GasGuard** is an Arduino-based fire and gas detection system that monitors air quality using an MQ-2 sensor. When the smoke or gas level exceeds a defined safety threshold, the system activates a buzzer and LED indicators to alert nearby individuals of the potential danger.

This project was created and simulated on **Tinkercad Circuits**, making it accessible for educational and prototyping purposes.

---

## 📦 Components Used

- Arduino Uno
- MQ-2 Gas/Smoke Sensor
- Piezo Buzzer
- RGB LED (Red, Green, Blue)
- Breadboard + Jumper Wires

---

## ⚙️ How It Works

- Continuously reads gas concentration from the sensor
- If the level exceeds a **predefined safety limit**:
  - 🔴 Red LED lights up
  - 🔊 Buzzer turns ON
- If safe:
  - 🟢 Green LED lights up
  - 🔇 Buzzer stays OFF

> Safety limit is set in the code and can be calibrated as needed.

---

## 💡 Code Overview

The code configures an analog smoke detector input and controls an RGB LED and buzzer based on sensor readings.

📂 View full code here: [gas_detector.ino](gas_detector.ino)

---

## 📸 Circuit Preview

![Circuit Preview](https://github.com/MadhurToshniwal/GasGuard-Tinkercad/blob/main/gasguard_circuit.png)


---

## 🔬 Simulation Platform

Built and tested using  
🔗 [Tinkercad Circuits](https://www.tinkercad.com/)

---

## 🚀 Future Enhancements

- LCD or OLED display for real-time gas level
- Mobile app integration (e.g., Blynk/Firebase alerts)
- Battery-powered deployment
- Internet-connected alerts (via ESP8266 or ESP32)

---

## 👨‍💻 Author

**Madhur Sunilkumar Toshniwal**  
🎓 B.Tech, Vellore Institute of Technology  
📧 [your.email@example.com](mailto:madhurtoshniwal03@gmail.com) • 🔗 [LinkedIn](https://linkedin.com/in/madhur-toshniwal) • 🐙 [GitHub](https://github.com/MadhurToshniwal)

---
