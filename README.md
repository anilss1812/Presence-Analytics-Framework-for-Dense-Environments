# Presence Analytics Framework for Dense Environments

An RFID-based real-time presence monitoring and safety framework designed for dense public environments such as temples, malls, auditoriums, and transport hubs.

## 🔍 Project Overview
This system authenticates individuals using RFID (MFRC522) at entry and exit points to maintain accurate occupancy counts. Environmental parameters such as temperature, humidity, and air quality are continuously monitored, and real-time data is pushed to a cloud dashboard using IoT.

## 🧠 System Architecture
- **LPC1768 (ARM Cortex-M3)** – Core controller
- **ESP32** – Cloud connectivity (MQTT)
- **MFRC522 RFID** – Entry/Exit authentication
- **DHT11** – Temperature & humidity sensing
- **MQ135** – Air quality monitoring
- **LCD + LEDs + Buzzer** – Local alerts & display
- **Servo Motor** – Automated gate control

## 🔁 Key Features
- Deterministic presence tracking (no estimation)
- Real-time occupancy count
- Automated entry/exit gate
- Emergency alert handling
- Missing person detection
- Cloud dashboard (Zoho IoT / MQTT)

## 📊 System Flow
- RFID Entry Authentication
- Occupancy Update
- Sensor Monitoring
- Cloud Data Upload
- Emergency Handling
- RFID Exit Logging
- Missing Person Detection

## 🧪 Technologies Used
- Embedded C (Bare-metal)
- SPI, UART, ADC
- MQTT, HTTP
- Zoho IoT Platform

## 📁 Folder Structure
