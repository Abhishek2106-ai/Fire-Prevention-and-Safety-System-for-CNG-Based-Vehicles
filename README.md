# Fire Prevention and Safety System for CNG Based Vehicles

## Overview

The **Fire Prevention and Safety System for CNG Based Vehicles** is an IoT-based safety solution developed using **Arduino UNO**. The project is designed to detect potential fire hazards such as gas leakage, flame, and abnormal temperature conditions inside CNG vehicles and respond automatically to minimize risk.

The system integrates multiple sensors with communication and safety modules to provide early detection, emergency alerts, and automatic fire suppression. It aims to improve passenger safety by enabling early hazard detection and automatic emergency response during critical situations.

---

## Features

* Gas Leakage Detection
* Flame Detection
* Smoke Monitoring
* Temperature Monitoring
* Automatic Water Pump Activation
* Buzzer Alert System
* GSM Emergency SMS Alert
* GPS Live Location Tracking
* LCD Display Monitoring
* Automatic Door Unlock System using Solenoid Lock
* Multi-Sensor Hazard Detection

---

## Technologies Used

* Arduino UNO
* Embedded C++
* IoT
* GSM Communication
* GPS Tracking
* Sensor Integration

---

## Hardware Components

* Arduino UNO
* MQ Gas Sensor
* Flame Sensor
* Smoke Sensor
* DHT11 Temperature Sensor
* GSM Module (SIM800L)
* GPS Module (Neo-6M)
* Relay Module
* Mini Water Pump
* Solenoid Lock
* 16×2 LCD Display
* Buzzer
* Motor Driver Module
* Bluetooth Module
* Battery Pack
* Jumper Wires

---

## Circuit Connections

| Component           | Arduino Pin |
| ------------------- | ----------- |
| MQ Gas Sensor       | A0          |
| Smoke Sensor        | A1          |
| Flame Sensor        | D2          |
| Buzzer              | D3          |
| Relay Module        | D4          |
| Solenoid Lock Relay | D5          |
| GSM Module          | D7, D8      |
| GPS Module          | D9, D10     |
| LCD Display         | I2C         |

---

## Working Principle

The system continuously monitors different parameters related to fire hazards using multiple sensors.

* The gas sensor detects combustible gas leakage.
* The flame sensor detects the presence of fire.
* The temperature sensor monitors abnormal temperature rise.

Whenever any hazardous condition is detected, the Arduino processes the sensor data and automatically performs the following actions:

* Activates the buzzer
* Turns on the water pump
* Unlocks the vehicle door using the solenoid lock
* Displays a warning message on the LCD
* Sends an emergency SMS using the GSM module
* Shares the current location using the GPS module

This automated response helps reduce damage and provides additional time for passengers to evacuate safely.

---

## Applications

* CNG Vehicles
* Smart Vehicle Safety Systems
* Fire Prevention Systems
* IoT-Based Monitoring
* Industrial Safety Applications

---

## Software Requirements

* Arduino IDE
* TinyGPS++ Library
* LiquidCrystal_I2C Library
* DHT Sensor Library
* SoftwareSerial Library

---

## Installation

### Clone the repository

```bash
git clone https://github.com/Abhishek2106-ai/Fire-Prevention-and-Safety-System-for-CNG-Based-Vehicles.git
```

### Open the project

Open the Arduino source code using:

* Arduino IDE
* Visual Studio Code with Arduino Extension

### Install required libraries

* TinyGPS++
* LiquidCrystal_I2C
* DHT Sensor Library
* SoftwareSerial

### Connect the hardware

Connect all sensors and modules according to the circuit diagram provided in the project.

### Upload the code

Compile and upload the Arduino sketch to the Arduino UNO board.

---

## Power Requirements

| Module        | Voltage     |
| ------------- | ----------- |
| Arduino UNO   | 5V          |
| GSM SIM800L   | 3.7V – 4.2V |
| GPS Neo-6M    | 3.3V – 5V   |
| Solenoid Lock | 12V         |
| Water Pump    | 6V – 12V    |

> An external power supply is recommended for the GSM module, water pump, and solenoid lock.

---

## Project Structure

```
├── Arduino_Code
├── Images
├── Patent
├── Report
├── Research_Paper
├── Components_List.txt
└── README.md
```

---

## Project Images



---

## Results

The developed prototype was successfully tested under different conditions.

* Gas leakage detection worked successfully.
* Fire detection and alarm system responded correctly.
* Automatic water pump activation was verified.
* GSM emergency messages were sent successfully.
* GPS location sharing worked as expected.
* LCD displayed warning messages correctly.
* Automatic door unlocking mechanism functioned properly during emergency conditions.

---

## Future Scope

* Mobile Application Integration
* Cloud-Based Monitoring
* AI-Based Fire Prediction
* Real-Time Vehicle Analytics
* Automatic Engine Shutdown
* IoT Dashboard Integration

---

## Challenges Faced

* GSM network instability
* Sensor calibration
* Power management for multiple modules
* Synchronization between communication modules

---

## Patent

Patent Application Published (A1) – Indian Patent Office.

**Title:** Fire Prevention and Safety System for CNG Based Vehicles

**Publication Number:** IN202511125067 A1

**Publication Date:** 30-01-2026


The patent document is available in the **Patent** folder.

---

## Research Paper

The research paper based on this project is available in the **Research_Paper** folder.

---

## Project Report

A detailed project report describing the design, implementation, and testing of the system is available in the **Report** folder.

---

## Team Contribution

This project was developed as a collaborative final-year engineering project.

### My Contribution

- Arduino Programming
- Sensor Integration
- Hardware Assembly
- Module Integration
- Testing and Debugging
- Solenoid Lock Integration

---

## Acknowledgment

This project was developed for academic and research purposes as part of a final-year engineering project. It is a prototype system and requires industrial-grade testing and validation before deployment in real-world vehicles.

---

## License

This project is shared for educational purposes. Please provide appropriate credit before using or modifying the work.

## Author

**Abhishek Singh**

Final Year B.Tech Project

If you found this project useful, consider giving it a ⭐ on GitHub.