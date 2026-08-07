# 🚗 VehicleGuard Pro
### Smart Telematics & Diagnostic Assistant with AI-Powered Health Analytics

![Platform](https://img.shields.io/badge/Platform-ESP32-blue)
![Protocol](https://img.shields.io/badge/Communication-CAN%20Bus-orange)
![IoT](https://img.shields.io/badge/IoT-MQTT-success)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
---

## 📖 Overview

**VehicleGuard Pro** is a next-generation IoT-based vehicle monitoring and diagnostic system that combines **CAN Bus communication**, **Artificial Intelligence**, **Digital Twin technology**, **Cloud Connectivity**, and **Real-time Analytics** to monitor vehicle health.

The project simulates and monitors more than **45 vehicle parameters**, predicts component health using AI algorithms, detects anomalies in real time, and displays information across multiple platforms including a Web Dashboard, LCD Display, Mobile Application, and Digital Twin interface.

---

## ✨ Features

- 🚘 Real-Time Vehicle Telemetry
- 🤖 AI-Based Vehicle Health Prediction
- 🔍 Predictive Maintenance
- 📡 CAN Bus Communication (250 kbps)
- 🌐 Live Web Dashboard
- 📱 Mobile Application
- 🖥 Digital Twin Visualization
- 📟 LCD Display Interface
- ☁ MQTT Cloud Connectivity
- 📍 GPS Tracking
- 📊 Health Analytics
- ⚠ Intelligent Fault Detection
- 🔔 Real-Time Alerts & Notifications

---

# System Architecture

```
                  Vehicle Simulator (ESP32)
                           │
                   MCP2515 CAN Bus
                           │
         ┌─────────────────┴─────────────────┐
         │                                   │
 AI Processing ESP32                 NodeMCU ESP8266
         │                                   │
         │                            Bluetooth HC-05
         │                                   │
         │                             Mobile App
         │
 ┌──────────────┬──────────────┬─────────────┐
 │              │              │             │
LCD Display  Web Dashboard  Digital Twin   MQTT Cloud
```

---

# Project Highlights

✔ 45+ Vehicle Parameters

✔ 17 CAN Message IDs

✔ AI Health Prediction

✔ Digital Twin

✔ GPS Integration

✔ Bluetooth Mobile App

✔ MQTT Cloud Monitoring

✔ Web Dashboard

✔ LCD Interface

✔ Real-Time Alerts

---

# Hardware Used

| Component | Quantity |
|------------|----------|
| ESP32 Development Board | 2 |
| NodeMCU ESP8266 | 1 |
| MCP2515 CAN Module | 3 |
| HC-05 Bluetooth Module | 1 |
| MPU6050 Sensor | 1 |
| NEO-6M GPS Module | 1 |
| 16x2 I2C LCD | 1 |
| Rotary Encoder | 1 |
| Push Buttons | 4 |
| Potentiometers | 3 |
| LEDs | 5 |
| Buzzer | 1 |

---

# Software & Technologies

- Arduino IDE
- ESP32 Framework
- ESP8266 Framework
- HTML
- CSS
- JavaScript
- MQTT
- CAN Protocol
- JSON
- MIT App Inventor
- Digital Twin
- AI Rule-Based Health Analytics

---

# Communication Technologies

- CAN 2.0B
- UART
- SPI
- I2C
- Bluetooth
- WiFi
- MQTT

---

# AI Health Monitoring

VehicleGuard Pro predicts the health of

- Engine
- Battery
- Brakes
- Engine Oil
- Overall Vehicle Health

The AI engine continuously analyzes sensor values and generates intelligent alerts for abnormal conditions.

---

# Parameters Monitored

### Engine

- RPM
- Engine Load
- Horsepower
- Torque
- Engine Hours

### Temperature

- Coolant Temperature
- Oil Temperature
- Exhaust Temperature
- Catalytic Converter Temperature

### Electrical

- Battery Voltage
- Alternator Voltage
- Battery Health
- State of Charge

### Brake System

- Brake Pad Wear
- Brake Fluid
- Brake Pressure
- Brake Temperature

### Tyres

- Pressure
- Temperature
- Wear

### Fuel

- Fuel Level
- Fuel Consumption
- Fuel Pressure

### GPS

- Latitude
- Longitude
- Altitude
- Speed
- Satellite Count

---

# Multi-Platform Visualization

✔ Responsive Web Dashboard

✔ AI Digital Twin

✔ Bluetooth Mobile Application

✔ LCD Dashboard

✔ MQTT Cloud Dashboard

---

# Project Workflow

```
Vehicle Inputs
      │
      ▼
ESP32 Vehicle Simulator
      │
      ▼
CAN Bus Communication
      │
      ▼
AI Processing ESP32
      │
      ├────────► LCD Display
      ├────────► Web Dashboard
      ├────────► Digital Twin
      ├────────► MQTT Cloud
      └────────► Bluetooth Node
                     │
                     ▼
                 Mobile App
```

---


# Future Improvements

- Machine Learning Based Prediction
- OBD-II Integration
- Firebase Cloud Storage
- Android & iOS App
- Voice Assistant Support
- OTA Firmware Updates
- Fleet Management Dashboard
- Predictive Maintenance Scheduling

---

# Applications

- Smart Vehicles
- Connected Cars
- Fleet Management
- Automotive Research
- Educational Projects
- Vehicle Health Monitoring
- Industrial Telematics
- Automotive IoT

---

# Performance

| Feature | Performance |
|----------|-------------|
| Vehicle Parameters | 45+ |
| CAN IDs | 17 |
| CAN Packet Loss | <0.1% |
| Web Response | <500 ms |
| AI Prediction Accuracy | >95% |
| System Cost | ₹4,875 |

---

# Author

**Eshwar Prasad Y**

Electronics & Communication Engineering

Embedded Systems | IoT | AI | Automotive Electronics | Digital Twin

Email: eshwargowda313@gmail.com

LinkedIn: linkedin.com/in/eshwar-prasad-y-a3043b370

---

# Acknowledgements

Special thanks to

- Arduino Community
- ESP32 Community
- EMQX MQTT
- MIT App Inventor
- Open Source Community

---
