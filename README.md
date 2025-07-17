# Soldier Tracking and Health Monitoring System

A real-time soldier tracking and health monitoring system built using IoT technologies, biomedical sensors, GPS/GSM modules, and FreeRTOS. This project is aimed at enhancing the safety, health awareness, and operational efficiency of military personnel in the field.

---

## 🔍 Overview

This system monitors vital health parameters—such as heart rate, body temperature, and gas exposure—and tracks the real-time location of soldiers using GPS. It uses an RTOS (FreeRTOS) for priority-based task scheduling and sends emergency alerts via a GSM module.

---

## 🧠 Key Features

- 💓 Real-time heart rate monitoring using Pulse Sensor  
- 🌡️ Body temperature monitoring with LM35  
- ☢️ Hazardous gas detection via MQ-5 sensor  
- 📍 GPS-based live location tracking (Neo 6M GPS)  
- 📲 GSM alerts to the base unit on abnormal conditions  
- 📶 MQTT-based communication for IoT cloud support  
- 🔔 Audible alert system using buzzer  
- ⏱️ FreeRTOS-based multitasking and priority scheduling  
- 🧪 Simulation tested using Proteus  
- ⚙️ Hardware implemented on Arduino Mega and ESP32  

---

## 🧰 Components Used

| Component               | Description                            |
|------------------------|----------------------------------------|
| Arduino Mega / ESP32   | Main microcontroller                   |
| Pulse Sensor            | Heart rate detection                   |
| LM35                   | Temperature sensing                     |
| MQ-5                   | Gas leakage detection                   |
| Neo 6M GPS             | Real-time GPS tracking                  |
| GSM Module             | Message transmission to base unit      |
| Buzzer                 | Audible alerts                         |
| FreeRTOS               | Real-Time Operating System for Arduino |

---

## 🖥️ Pin Connections

| Component         | Arduino Pin           |
|------------------|------------------------|
| Pulse Sensor      | A1 (Analog)            |
| LM35              | A0 (Analog)            |
| MQ-5 Gas Sensor   | A2 (Analog), D5        |
| GPS Module        | Rx – D3, Tx – D4       |
| GSM Module        | Tx – D10, Rx – D11     |
| Buzzer            | D8                    |

---

## 🧪 Simulation & Testing

- **Software Used**: Proteus (for circuit simulation), Arduino IDE  
- **Simulation Output**: Heart rate, temperature, and gas values displayed on virtual terminal.  
- **Hardware Output**: Serial Monitor output with sensor data and GPS coordinates. Alert messages successfully sent via GSM.


