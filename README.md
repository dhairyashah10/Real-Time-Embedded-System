# Real-Time Environment Monitoring System (RTES)

A real-time environment-monitoring system built with C++ and IoT sensors to measure temperature and humidity. This project demonstrates real-time data acquisition, sensor integration, and embedded systems programming with a focus on reliability and scalability.

## 🚀 Motivation
The goal of this project was to design a lightweight, real-time system capable of continuously monitoring environmental conditions such as temperature and humidity. This kind of system is commonly used in smart homes, industrial monitoring, agriculture, and health-sensitive environments.

## 🛠️ Technologies Used
- C++
- DHT11 Temperature & Humidity Sensor
- Embedded Systems / IoT
- Real-Time Data Processing
- GCC / Arduino-compatible toolchain (depending on setup)

## 📐 System Architecture
- Sensor layer collects temperature and humidity data using DHT11
- Data is processed in real time using optimized C++ logic
- Modular design allows easy extension to additional sensors

## 📂 Project Structure
src/

├── main.cpp # Entry point and application flow

├── dht11.cpp # Sensor logic and data reading

└── dht11.h # Sensor interface definitions

docs/

└── RTES_Project_Report.pdf

