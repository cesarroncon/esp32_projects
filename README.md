# esp32_projects

# 📡 ESP32 Project Collection: WebSockets, Distance Sensors & LED Feedback

## 📌 Introduction

This repository contains a collection of small ESP32-based projects designed to explore the capabilities of the ESP32 microcontroller.  
The **ESP32** is a powerful and affordable Wi-Fi and Bluetooth-enabled microcontroller known for its versatility, high processing power, and wide range of features. It supports multiple protocols such as **Wi-Fi**, **Bluetooth**, **BLE**, **SPI**, **I2C**, **PWM**, and **ADC**, making it an excellent platform for a wide variety of IoT and embedded applications.

These projects are examples of what can be built using an ESP32 — but the possibilities extend far beyond these. The ESP32 can be used in everything from home automation, sensors, telemetry systems, and remote control devices to real-time data monitoring and interactive interfaces.

---

## 🚀 About the Projects

### ✅ 1. **WebSocket Channel over Wi-Fi**
A simple WebSocket server hosted on the ESP32, allowing real-time bi-directional communication between the microcontroller and a client device (like a browser or app) over a local Wi-Fi network.  
This setup is ideal for applications that require instant updates, such as dashboards, sensor data displays, or remote control interfaces.

---

### ✅ 2. **Distance Sensor with Wi-Fi Access Point Mode**
An ESP32 project that reads distance measurements from an ultrasonic sensor (HC-SR04 or similar) and displays the data via a locally hosted web page.  
In this case, the ESP32 acts as a standalone **Wi-Fi access point**, meaning no external router is needed — you can connect your phone or PC directly to the ESP32’s Wi-Fi signal and view the data through a web browser.

---

### ✅ 3. **Distance Sensor with LED Feedback and FTG Integration**
A more complex setup combining:
- **A distance sensor**
- **LED indicators** (to visualize distance thresholds)
- And integration with an **FTG (custom module or feature you might have)**

In this project:
- The ESP32 reads distance values
- Depending on the measured distance, it controls multiple LEDs to provide visual feedback
- Additionally, it connects via Wi-Fi and/or WebSockets for remote monitoring or triggering other devices

---

## 🎯 Purpose

These projects aim to showcase the flexibility and capability of the ESP32, providing examples for beginners and enthusiasts interested in exploring IoT applications, wireless communication, and interactive hardware setups.

---

## 📣 Final Note

The ESP32 is a fantastic platform for countless projects — from simple sensor nodes to complex automation systems.  
These examples only scratch the surface of what can be achieved with it. I encourage anyone interested in electronics, IoT, or embedded systems to experiment with the ESP32, as it opens the door to endless creative possibilities.

---

