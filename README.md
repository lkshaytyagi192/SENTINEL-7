# 🚁 SENTINEL-7
### AI-Powered Autonomous Fire Detection & Monitoring Drone

![Python](https://img.shields.io/badge/Python-3.11-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![STM32](https://img.shields.io/badge/STM32-Embedded-red)
![ArduPilot](https://img.shields.io/badge/ArduPilot-Autonomous-orange)
![Mission Planner](https://img.shields.io/badge/Mission%20Planner-GCS-blueviolet)
![Status](https://img.shields.io/badge/Status-Under%20Development-success)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

# 📖 Overview

**SENTINEL-7** is an AI-powered autonomous drone designed for **early wildfire detection, environmental monitoring, and emergency response**.

The system combines **computer vision, embedded systems, environmental sensors, artificial intelligence, and autonomous flight** to detect potential fire hazards before they become uncontrollable.

Instead of relying solely on thermal cameras or manual inspections, SENTINEL-7 continuously monitors forests, industrial areas, and remote locations using onboard intelligence and autonomous navigation.

---

# 🎯 Project Objectives

- Detect fire at an early stage
- Detect smoke using Computer Vision
- Measure environmental conditions
- Predict fire risk using AI
- Perform autonomous waypoint missions
- Send real-time alerts
- Stream live video
- Generate mission reports
- Enable future swarm drone deployment

---

# 🌍 Problem Statement

Wildfires destroy millions of hectares of forest every year.

Current monitoring methods have limitations:

- Human patrols are expensive
- Satellite updates are delayed
- CCTV coverage is limited
- Manual inspection is dangerous

SENTINEL-7 aims to solve these problems through autonomous aerial monitoring.

---

# 🚀 Features

## 🔥 Fire Detection

- Flame Detection
- Smoke Detection
- High Temperature Detection
- Environmental Hazard Detection

---

## 🤖 Artificial Intelligence

- Fire Risk Prediction
- Image Classification
- Smoke Detection Model
- Data Fusion
- Future Fire Spread Prediction

---

## 📷 Computer Vision

Using OpenCV:

- Image Processing
- HSV Color Detection
- Thresholding
- Contour Detection
- Shape Detection
- Object Detection
- Video Streaming

---

## 🚁 Autonomous Flight

Using ArduPilot:

- Auto Missions
- Guided Mode
- Loiter
- RTL (Return to Launch)
- Waypoint Navigation
- Mission Planner Integration

---

## 📡 Live Telemetry

The drone continuously transmits:

- GPS Coordinates
- Altitude
- Speed
- Battery Voltage
- Flight Mode
- Sensor Data

---

## 🌡 Environmental Monitoring

The drone measures:

- Temperature
- Humidity
- Gas Concentration
- Smoke Level
- Air Quality

---

# 🛠 Hardware Used

## Flight Controller

- APM 2.8

## GPS

- u-blox M8N

## Camera

- ESP32-CAM
- OV3660 Camera Module

## Microcontroller

- STM32

## Sensors

- MQ Series Smoke Sensor
- Temperature Sensor
- Humidity Sensor
- Gas Sensor

## Communication

- Telemetry Radio
- WiFi
- MAVLink

## Frame

- 550mm Quadcopter

---

# 💻 Software Stack

## Languages

- C
- C++
- Python

## Embedded

- STM32CubeIDE
- HAL Drivers

## Computer Vision

- OpenCV

## AI

- TensorFlow
- Scikit-Learn

## Drone Software

- ArduPilot
- Mission Planner
- MAVLink

## Development Tools

- VS Code
- Git
- GitHub
- Logic Analyzer

---

# 🧠 System Architecture

```
                    Environmental Sensors
                           │
                           ▼
                    STM32 Microcontroller
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
     ESP32 Camera      Flight Controller   GPS
          │                │               │
          └────────────┬───┴───────────────┘
                       ▼
                AI Processing
                       │
             Fire Risk Prediction
                       │
          Live Telemetry & Alerts
                       │
             Mission Planner GCS
```

---

# 🔄 Working Principle

1. Drone takes off autonomously.
2. Follows predefined waypoint mission.
3. Captures live video.
4. Reads environmental sensor values.
5. Detects smoke and fire using OpenCV.
6. AI predicts fire severity.
7. Drone sends alerts with GPS coordinates.
8. Operator receives live video and telemetry.
9. Drone returns automatically when mission completes.

---

# 📂 Project Structure

```
SENTINEL-7/

│
├── AI/
│   ├── Fire Prediction Model
│   ├── Dataset
│   └── Training
│
├── Computer Vision/
│   ├── Fire Detection
│   ├── Smoke Detection
│   ├── Image Processing
│   └── Video Streaming
│
├── STM32/
│   ├── Sensor Drivers
│   ├── UART
│   ├── SPI
│   └── I2C
│
├── ESP32-CAM/
│
├── ArduPilot/
│   ├── Mission Files
│   ├── Parameters
│   └── Logs
│
├── Documentation/
│
├── Images/
│
├── Videos/
│
└── README.md
```

---

# 📊 Sensor Data Example

| Parameter | Value |
|-----------|------|
| Temperature | 42°C |
| Humidity | 28% |
| Smoke | High |
| Gas Level | Medium |
| Battery | 86% |
| GPS | Available |

---

# 📡 Telemetry

The Ground Control Station displays:

- Live Camera Feed
- GPS Position
- Flight Path
- Battery Status
- Flight Mode
- Sensor Readings
- Fire Alerts

---

# 🔥 Future Enhancements

- Thermal Camera Integration
- YOLOv11 Fire Detection
- Swarm Drone Coordination
- LTE/5G Connectivity
- Edge AI Inference
- Real-Time Cloud Dashboard
- Autonomous Charging Station
- Precision Water Release Module
- Forest Mapping
- GIS Integration

---

# 🎯 Applications

- Forest Fire Monitoring
- Industrial Safety
- Oil & Gas Facilities
- Wildlife Protection
- Disaster Management
- Smart Cities
- Military Surveillance
- Agricultural Monitoring

---

# 📈 Current Development Status

✅ Drone Platform

✅ Autonomous Flight

✅ Mission Planner Integration

✅ Waypoint Missions

✅ Computer Vision Pipeline

✅ Sensor Integration

🚧 AI Fire Prediction

🚧 Real-Time Alert System

🚧 Cloud Dashboard

🚧 Thermal Imaging

---

# 🤝 Contributing

Contributions are welcome!

If you would like to improve SENTINEL-7:

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Submit a Pull Request.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Lakshay Tyagi**

B.Tech Computer Science Engineering

Embedded Systems | Autonomous Robotics | UAV Software | Computer Vision

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile

---

# ⭐ If you found this project useful

Please consider giving this repository a ⭐ to support future development.

```

## Suggested repository folders

To make the repository look professional, organize it like this:

```text
SENTINEL-7/
├── assets/
│   ├── images/
│   ├── architecture/
│   └── demo/
├── docs/
├── firmware/
│   ├── stm32/
│   ├── esp32_cam/
│   └── ardupilot/
├── ai/
├── computer_vision/
├── telemetry/
├── datasets/
├── mission_files/
├── hardware/
├── tests/
├── LICENSE
├── requirements.txt
└── README.md
```

This README is comprehensive enough for a portfolio project while remaining suitable for GitHub, internship applications, and robotics or embedded software roles.
