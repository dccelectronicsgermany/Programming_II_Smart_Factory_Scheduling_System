# 🏭 Smart Factory Assistant
### AI-Based Predictive Maintenance and Intelligent Job Scheduling System for Smart Manufacturing

> A Java-based Smart Factory Management System that combines **machine monitoring**, **predictive maintenance**, and **intelligent job scheduling** to improve manufacturing efficiency, reduce downtime, and support Industry 4.0 applications.

---

## 📌 Project Overview

The **Smart Factory Assistant** is an intelligent manufacturing management system developed as part of the **Programming II** course at **Hochschule Hamm-Lippstadt**.

The application continuously monitors industrial machines, predicts potential failures using health-score calculations, generates maintenance alerts, and intelligently schedules manufacturing jobs to the most suitable machines.

The project demonstrates practical implementation of **Object-Oriented Programming (OOP)** principles together with software engineering concepts applicable to modern smart factories.

---

# Team Members

### Student 1
**Name:** Daniel Chidi Chimezie

**Matriculation Number:** 1230515

### Student 2
**Name:** Ronald Bukoola

**Matriculation Number:** 1234012

---

# Course Information

| Item | Details |
|------|---------|
| Course | Programming II |
| Professor | Martin Sonntag |
| University | Hochschule Hamm-Lippstadt |

---

# Features

- Machine Monitoring
- Predictive Maintenance
- Intelligent Job Scheduling
- Maintenance Alert Generation
- Machine Health Calculation
- Dashboard Reporting
- Job Management
- Performance Monitoring

---

# Functional Requirements

## FR1 – Machine Monitoring

- Store machine information
- Monitor machine temperature
- Monitor machine vibration
- Update machine status

---

## FR2 – Predictive Maintenance

- Calculate machine health score
- Detect abnormal machine conditions
- Predict possible failures
- Generate maintenance alerts

---

## FR3 – Job Management

- Create manufacturing jobs
- Assign jobs to machines
- Track job completion
- Update job status

---

## FR4 – Intelligent Scheduling

- Recommend the best machine
- Prioritize urgent jobs
- Avoid overloaded machines
- Optimize machine utilization

---

## FR5 – Reporting Dashboard

- Display machine status
- Display maintenance alerts
- Show job progress
- Visualize production information

---

# Non-Functional Requirements

### NFR1 – Usability

- Simple interface
- Easy navigation
- User-friendly dashboard

### NFR2 – Performance

- Fast response time
- Efficient scheduling
- Low processing delay

### NFR3 – Reliability

- Accurate calculations
- Stable operation
- Reliable maintenance predictions

### NFR4 – Scalability

- Support additional machines
- Support more sensors
- Support larger production environments

---

# System Architecture

The project consists of the following major classes:

## Machine

Responsible for:

- Machine information
- Temperature
- Vibration
- Health score
- Machine status

### Methods

- updateStatus()
- calculateHealthScore()
- displayInformation()

---

## Sensor

Responsible for collecting machine sensor data.

### Methods

- readValue()
- sendData()

---

## MaintenanceManager

Responsible for predictive maintenance.

### Methods

- calculateHealthScore()
- predictFailure()
- generateAlert()

---

## Job

Responsible for manufacturing jobs.

### Methods

- startJob()
- completeJob()

---

## Scheduler

Responsible for intelligent scheduling.

### Methods

- assignJob()
- optimizeSchedule()
- recommendMachine()

---

## Dashboard

Responsible for visualization.

### Methods

- displayMachines()
- displayJobs()
- displayAlerts()

---

# Predictive Maintenance Formula

The current machine health score is calculated as:

```text
Health Score = 100 − (0.4 × Temperature Risk + 0.6 × Vibration Risk)
```

Where

- Higher Health Score = Healthier Machine
- Lower Health Score = Higher Failure Risk

---

# Example Dashboard

The dashboard displays:

- Number of Machines
- Healthy Machines
- Maintenance Alerts
- Active Jobs
- Machine Health
- Job Progress
- Maintenance Warnings

---

# Possible Hardware Integration

The software can be integrated with:

- Arduino Uno WiFi
- ESP32 DevKitC
- Raspberry Pi
- DS18B20 Temperature Sensor
- Vibration Sensors
- Industrial PLCs
- IoT Gateways

---

# Technologies Used

- Java
- JavaFX
- MySQL
- Object-Oriented Programming
- Collections Framework
- Exception Handling
- File Handling

---

# Programming Concepts Demonstrated

- Classes
- Objects
- Encapsulation
- Inheritance
- Polymorphism
- Interfaces
- Collections
- Algorithms
- Exception Handling
- File Handling
- GUI Development

---

# Expected Outcomes

The project aims to:

- Reduce unexpected machine failures
- Improve maintenance planning
- Increase production efficiency
- Demonstrate object-oriented programming concepts
- Simulate a real-world smart factory application

---

# Project Structure

```
SmartFactoryAssistant/
│
├── src/
│   ├── Machine.java
│   ├── Sensor.java
│   ├── MaintenanceManager.java
│   ├── Scheduler.java
│   ├── Job.java
│   ├── Dashboard.java
│   ├── Main.java
│   └── utils/
│
├── database/
│   └── smart_factory.sql
│
├── resources/
│
├── images/
│
├── README.md
│
└── pom.xml
```

---

# Future Improvements

- Machine Learning Failure Prediction
- IoT Sensor Integration
- MQTT Communication
- REST API
- Cloud Dashboard
- Mobile Application
- Real-Time Analytics
- Digital Twin Integration
- Predictive Scheduling using AI

---

# Learning Outcomes

After completing this project, students will understand:

- Object-Oriented Programming
- Software Design
- UML Class Design
- Smart Manufacturing
- Industry 4.0 Concepts
- Predictive Maintenance
- Intelligent Scheduling
- Java Application Development

---

# License

This project is developed for educational purposes as part of the **Programming II** course at **Hochschule Hamm-Lippstadt**.

---

# Acknowledgements

Special thanks to

**Prof. Martin Sonntag**

for guidance throughout the Programming II course.

---

## Screenshot

![Smart Factory Assistant Dashboard](image(493).png)

---

## Authors

**Daniel Chidi Chimezie**  
Matriculation Number: **1230515**

**Ronald Bukoola**  
Matriculation Number: **1234012**

Hochschule Hamm-Lippstadt
Programming II
2026
