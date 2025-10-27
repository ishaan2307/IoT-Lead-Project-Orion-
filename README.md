# Project Orion – IoT Lead (RedBack Operations)

## Overview  
**Project Orion** was developed at **RedBack Operations** with the goal of designing an integrated IoT-based **player tracking suit** and **crowd monitoring software**. The system aimed to enhance safety, performance analytics, and event monitoring through real-time sensor data acquisition, wireless communication, and live visualization.

As the **IoT Lead**, I was responsible for leading a 5-member team to implement the sensor network, develop data pipelines, and ensure system stability across multiple environments.

---

## Key Contributions  

### 1. GPS Sensor Optimization  
- Configured and optimized GPS modules to achieve **~5 cm tracking accuracy** for athlete movement across the field.  
- Implemented smoothing and interpolation algorithms to handle signal noise and ensure stable tracking even in dynamic conditions.  
- Documented every stage of calibration, testing, and integration for knowledge transfer and reproducibility.  

### 2. Cross-Sensor Integration  
- Guided teammates in integrating **accelerometer** and **heart rate detection** sensors into the player suit.  
- Established synchronization protocols to align data timestamps and ensure consistent readings across all modules.  
- Contributed to early-stage fusion algorithms for motion and health data correlation.  

### 3. Data Architecture Migration  
- Led the backend transition from **NoSQL (MongoDB)** to **SQL (MySQL)**, improving data consistency and relational querying.  
- Designed database schemas optimized for real-time sensor data storage and retrieval.  
- Streamlined backend access for data visualization tools and analytics dashboards.  

### 4. MQTT Broker Setup & Communication  
- Deployed and configured **Mosquitto MQTT Broker** on the company’s virtual machine to enable **real-time communication** between IoT devices and backend services.  
- Established secure publish/subscribe channels for player suit data and live crowd monitoring feeds.  
- Ensured low-latency, high-frequency message transmission for accurate real-time analysis.  

### 5. Documentation & Leadership  
- Authored detailed technical documentation for all system components, communication flows, and data-handling logic.  
- Collaborated across hardware, networking, and software teams to resolve bottlenecks and align deliverables.  

---

## Tools & Technologies  
**Hardware:** Raspberry Pi, GPS Module, Accelerometer, Heart Rate Sensor  
**Software:** Python, MQTT (Mosquitto), MySQL, Power BI, Node-RED  
**Protocols:** MQTT, HTTP, TCP/IP  
**Version Control:** Git, GitHub  

---

## Outcome  
Project Orion successfully delivered a **real-time IoT platform** capable of tracking player movements and crowd activity simultaneously. The system achieved **sub-decimetre tracking accuracy**, ensured robust data communication, and demonstrated scalable design for future smart sports applications.
