# maincrafts-embedded-system

# 🌡️ Smart Temperature Monitor using Arduino

A simple Embedded Systems and IoT mini project that monitors ambient temperature using an LM35 temperature sensor and Arduino UNO. When the measured temperature exceeds a predefined threshold, an LED alert is activated.

---

## 📌 Project Overview

This project demonstrates the fundamentals of Embedded Systems by integrating a temperature sensor with an Arduino microcontroller. It continuously monitors temperature and provides a visual alert when the temperature exceeds a safe limit.

This project was developed as part of an **Embedded Systems & IoT Internship Task**.

---

## 🚀 Features

- Real-time temperature monitoring
- Threshold-based LED alert
- Low-cost implementation
- Easy to expand into an IoT system using ESP32
- Beginner-friendly Arduino project

---

## 🛠 Hardware Used

- Arduino UNO
- LM35 Temperature Sensor
- LED
- 220Ω Resistor
- Breadboard
- Jumper Wires
- USB Cable

---

## 💻 Software Used

- Arduino IDE
- Tinkercad Circuits (Simulation)
- Wokwi (Optional)

---

## ⚙️ Working Principle

1. LM35 measures ambient temperature.
2. Arduino reads the analog voltage from the sensor.
3. Temperature is calculated in Celsius.
4. If temperature exceeds the threshold (30°C), the LED turns ON.
5. Otherwise, the LED remains OFF.

---

## 🔌 Circuit Connections

| LM35 | Arduino |
|------|----------|
| VCC | 5V |
| GND | GND |
| OUT | A0 |

LED

- Positive → Digital Pin 8
- Negative → GND through 220Ω resistor


---

## 📈 Future Improvements

- ESP32 Wi-Fi Integration
- Mobile App Notifications
- Cloud Data Logging
- OLED Display
- Buzzer Alert
- IoT Dashboard

---

## 🎯 Applications

- Smart Homes
- Industrial Temperature Monitoring
- Server Rooms
- Greenhouses
- Laboratories

---

## 📚 Learning Outcomes

- Embedded Systems Basics
- Arduino Programming
- Analog Sensor Interfacing
- Threshold-Based Control
- IoT Fundamentals

---

## 👨‍💻 Author

**Pavan Kuamr**
