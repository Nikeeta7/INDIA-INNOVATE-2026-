# INDIA-INNOVATE-2026-
# Earth Doom Bots: Hyper-Local AQI & Pollution Mitigation Dashboard 🌍🤖

**Project for India Innovates 2026 | Domain: Urban Solutions**

This repository contains the architecture, ML models, and hardware integration for an **Autonomous Mobile Robot** system designed to solve the "City Average" blind spot in air quality monitoring. Unlike static sensors, this system physically targets and purifies air in high-pollution hotspots across Delhi's 272 wards.

---

## Video Link:- 
*https://drive.google.com/file/d/1lc1N34Gi06izffGy-99bAJ18fbjghRI8/view?usp=sharing

## 🚀 The Problem & Solution

### The Gap
*   **City Averages Hide Reality:** No ward-wise AQI tracking exists currently.
*   **Blind Pollution Sources:** Systems cannot detect localized causes like construction dust or biomass burning in real-time.
*   **No Physical Mitigation:** Existing solutions are passive; they monitor but do not clean.

### Our Solution
A modular **Autonomous Air Purifier Robot** integrated with an **ML-powered intelligence dashboard**.
*   **Mobile Purification:** Actively cleans air ($500\text{ m}^3\text{/hr}$) while collecting data.
*   **Source Identification:** Random Forest models detect specific pollution causes.
*   **Predictive Analytics:** Bi-LSTM models forecast ward-level AQI for 24–72 hours.

---

## 🛠️ Tech Stack

### Hardware Components
*   **Main Controller:** Raspberry Pi 4 (Navigation, SLAM, Robot Brain).
*   **IoT Gateway:** ESP32 (Sensor data collection).
*   **Actuators:** Arduino Uno (Motor/fan/pump control).
*   **Sensors:** MQ2/MQ135 (Gas), DHT22 (Temp/Humidity), LIDAR (Mobility).
*   **Triple Filtration:** HEPA (99% PM2.5 capture), Moss Walls (20% $CO_2$ absorption), and Microalgae tanks (15% $NO_x$ removal).

### Software & Frameworks
*   **Robotics:** ROS (Robot Operating System).
*   **Data Transmission:** MQTT Protocol.
*   **Databases:** TimescaleDB (Time-series) & MongoDB.
*   **ML Pipeline:** Python (Bi-LSTM for forecasting, Random Forest for source classification).
*   **Communication:** Node-RED Dashboard & WhatsApp Business API for citizen alerts.

---

## 🏗️ System Architecture

1.  **Data Acquisition:** LoRa sensors and mobile robots stream AQI and environmental data to the Cloud.
2.  **Intelligence Layer:** ML models perform source detection and AQI forecasting.
3.  **Communication:** Data is visualized on an Admin Dashboard with automated policy triggers.
4.  **Physical Mitigation:** Robots auto-navigate to high-pollution wards using LIDAR and deploy the filtration system.

---

## 📊 Comparison: Our Solution vs. Existing Systems


| Feature | Earth Doom Bots | Existing Solutions |
| :--- | :--- | :--- |
| **Monitoring** | Hyper-local, Ward-wise mobile data | City-wide averages only |
| **Mitigation** | Autonomous Robot Purification | Passive/static sensors, no cleaning |
| **Intelligence** | ML Source ID & 72hr Forecasts | Blind to localized causes |
| **Delivery** | WhatsApp Alerts & Auto Policy Recs | Manual GRAP, Generic Warnings |
| **Cost** | Low-cost solar robots | High-cost static stations |

*[Source: Project USP Section 0.1.7]*

---

## 👥 The Team: Earth Doom Bots (GGSIPU)
*   **Sahil Khan** (ME)
*   **Ayush Kumar** (ME)
*   **Nikeeta** (CS)
*   **Piyush Kumar** (IT)
*   **Pooja** (CS)
*   **Deepali Bansal** (CS)

---

## 🔗 References
*   [Central Pollution Control Board (CPCB)](https://cpcb.nic.in)
*   [Delhi Pollution Control Committee (DPCC)](https://delhigovt.nic.in)
*   [Robot Operating System (ROS)](https://ros.org)
*   [Raspberry Pi Documentation](https://raspberrypi.org)

* <img width="1904" height="1079" alt="image" src="https://github.com/user-attachments/assets/93ad79a2-5ec2-44a6-881e-b29950a6b1a7" />

