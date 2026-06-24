# 🌊 Wireless Flood Detection and Environmental Monitoring System

## 📌 Project Overview

The **Wireless Flood Detection and Environmental Monitoring System** is an intelligent early-warning solution designed to detect water intrusion and monitor environmental conditions in real time. The system utilizes wireless RF communication to transmit flood alerts from a remote sensing node to a monitoring station, enabling rapid response to potential flooding events.

The architecture consists of a **Transmitter Unit** and a **Receiver Unit**. When water is detected by the transmitter, an alert is sent via a 433 MHz RF communication link. Upon receiving the alert, the receiver activates visual and audible warning mechanisms while simultaneously monitoring water depth, temperature, and humidity.

The collected data is displayed on a local LCD screen and an ESP32-powered monitoring dashboard, providing users with real-time situational awareness and alarm management capabilities.

---

## ✨ Key Features

* 🚨 Real-time flood and water detection
* 📡 Wireless communication using 433 MHz RF modules
* 🔔 Instant visual and audible alerts
* 📏 Water depth measurement using an ultrasonic sensor
* 🌡️ Temperature monitoring using DHT11
* 💧 Humidity monitoring using DHT11
* 🖥️ ESP32-based monitoring dashboard
* 📟 Local 16×2 LCD display
* 🔕 Hardware-based buzzer mute functionality
* 🔄 Interface-based alarm reset mechanism
* 🔋 Portable battery-powered operation



## 🔧 Hardware Components

### Transmitter Unit

* ATmega328P Microcontroller
* Water Detection Sensor
* 433 MHz RF Transmitter Module
* Status LED
* Battery Power Supply

### Receiver Unit

* ATmega328P Microcontroller
* 433 MHz RF Receiver Module
* ESP32 Development Board
* Ultrasonic Sensor
* DHT11 Temperature & Humidity Sensor
* 16×2 LCD Display
* Alarm LEDs
* Buzzer
* Push Button
* Logic IC-Based Alarm Control Circuit
* Battery Power Supply

---

## ⚙️ Working Principle

1. The water sensor continuously monitors for the presence of water.
2. When water is detected, the transmitter ATmega328P generates an alert signal.
3. The alert is transmitted wirelessly using the 433 MHz RF module.
4. The receiver unit receives the alert and activates warning LEDs and the buzzer.
5. The ultrasonic sensor measures the current water depth.
6. The DHT11 sensor measures temperature and humidity.
7. The ESP32 processes and displays all monitoring data through the dashboard interface.
8. Users can temporarily mute the buzzer using the hardware push button.
9. The alarm status can be reset through the monitoring interface.

---

## 💻 Software Requirements

* Arduino IDE
* ESP32 Board Package
* RF Communication Libraries
* DHT Sensor Library
* LiquidCrystal Library
* Embedded C/C++

---

## 🎯 Applications

* Flood Early Warning Systems
* Indoor Flood Monitoring
* Basement Water Leakage Detection
* Drainage Monitoring
* River and Canal Monitoring
* Water Tank Overflow Detection
* Environmental Monitoring
* Smart Disaster Management Systems

---

## 🚀 Future Enhancements

* LoRa Long-Range Communication
* GSM/SMS Alert Notifications
* Cloud-Based Data Logging
* Mobile Application Integration
* IoT Remote Monitoring
* AI-Based Flood Prediction
* Historical Data Analytics
* Multi-Node Sensor Network


