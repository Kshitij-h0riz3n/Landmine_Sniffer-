# 🔥 Landmine_Sniffer

A rugged, sensor-packed tactical robot designed for **real-time landmine detection**, **environmental monitoring**, **live surveillance**, and **Wi-Fi-based electronic attacks**.

Built for **defense & field recon**, this tank integrates multiple sensors, wireless tech, and offensive capabilities into one compact platform.

---

## 🧠 System Overview

| Module | Description |
|--------|-------------|
| 🔍 **Metal Detector** | Detects buried landmines using electromagnetic induction. |
| 📍 **GPS Module (Neo-7M)** | Sends precise coordinates when a landmine is detected. |
| 🌡️ **DHT11 Sensor** | Monitors basic humidity and temperature to assess terrain conditions. |
| ☠️ **MQ-5 Gas Sensor** | Detects flammable and hazardous gases (for chemical/bio threat detection). |
| 🎥 **ESP32-CAM (with Buck-Boost Converter)** | Streams live video from the tank. Converter ensures stable voltage for the cam. |
| 📶 **ESP8266 (ESP-07)** | Used for **Wi-Fi Deauthentication** and **Flooding Attacks** (jamming enemy communication). |
| 🧠 **ESP32 Dev Board** | Acts as the main controller for sensor data, video streaming, and communication. |

---

## 🔧 Features

- 🔔 **Landmine Detection with GPS Alerts**
- 🌍 **Basic Environmental Monitoring (Temp + Humidity)**
- 📹 **Live Video Surveillance (ESP32-CAM)**
- ☣️ **Gas Detection using MQ-5**
- 💥 **Wi-Fi Deauth & Flood Attacks via ESP8266**
- ⚡ **Voltage Regulation with Buck-Boost Converter**
- 🔄 **Modular System – Easy to Expand**

---

## 🔌 Hardware Used

- **ESP32 Dev Board**
- **ESP32-CAM Module**
- **ESP8266 ESP-07**
- **Metal Detector Module** (DIY or commercial coil + op-amp)
- **DHT11 Sensor**
- **MQ-5 Gas Sensor**
- **Neo-7M GPS Module**
- **Buck-Boost Converter** (for ESP32-CAM voltage stability)
- **Motor Driver (L298N / L9110S)**
- **Chassis with DC Motors**
- **Li-ion Battery Pack / Power Supply**
- Misc: wires, connectors, PCB or perfboard

---

## 🛠️ Software Features

- Firmware for ESP32 & ESP8266 written in Arduino IDE
- Serial/UART communication between ESP32 ↔ ESP8266
- Live camera stream via ESP32-CAM web server
- GPS data sent to serial monitor / remote module
- Wi-Fi attack firmware (e.g., modified ESP8266 Deauther)
- Basic sensor dashboard (OLED or Serial Monitor based)

---

## 🧪 How It Works

1. **Metal Detector** detects underground landmines.
2. **ESP32** gets **GPS data** from Neo-7M and logs location.
3. **DHT11** and **MQ-5** sensors monitor environmental safety.
4. **ESP32-CAM** streams live visuals using a regulated power supply (buck-boost).
5. **ESP8266** performs **Deauth / Wi-Fi flood attacks** for disrupting enemy networks.

---

## 🚀 Future Scope

- Solar-powered energy setup ☀️
- Android app with GPS map and camera view 📱
- Long-range RF or LoRa communication 📡
- AI-based object recognition with ESP32-CAM 🧠

---

## 📸 Screenshots / Demo

> Add photos, camera snaps, or demo links here.

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).

---

## 💬 Author

**Kshitij Shrawade**  
`Electronics & Telecommunication Engg | DY Patil Institute of Technology`  
📧 [Add your contact if needed]

