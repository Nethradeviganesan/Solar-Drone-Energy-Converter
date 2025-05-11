# ☀️ Solar Drone Energy Converter

This project is designed to monitor and manage solar energy for drone applications. It uses an **Arduino** to read real-time voltage from a **solar panel system**, and a **Java-based GUI** to display and simulate the voltage readings.

---

## 🚀 Project Overview

Drones have limited battery capacity. By integrating solar power, we can **extend flight time** or **recharge batteries** on-the-go. This system includes:

- Real-time voltage monitoring via Arduino
- Graphical User Interface (Java Swing)
- Circuit diagram with solar panel, battery, and voltage divider
- Simple simulation if hardware is not connected

---

## ⚙️ Components Used

| Component        | Description                      |
|------------------|----------------------------------|
| Solar Panel      | 6V - provides energy input       |
| 1N5819 Diode     | Prevents reverse current         |
| Li-ion Battery   | Stores solar energy              |
| Arduino Uno      | Reads solar voltage              |
| Voltage Divider  | Steps down voltage to safe level |
| Java GUI (Swing) | Desktop app to display voltage   |

---

## 🧠 Working Principle

- Solar panel charges the battery.
- Arduino reads voltage via analog pin (A0).
- Java GUI receives voltage (can be extended via Serial or Wi-Fi).
- Real-time display helps in energy monitoring.

---

## 🖥️ Java GUI Preview

The GUI is written in Java using Swing and simulates live voltage updates.

![GUI Screenshot](circuit_diagram.png)

> You can modify it to read real serial values from Arduino via USB.

---

## 🔌 Circuit Diagram

See `circuit_diagram.png` for full setup including:
- Solar panel input
- Diode & battery connection
- Voltage divider output to Arduino

---

## 📁 Project Structure

