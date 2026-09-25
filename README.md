# 🚗 Smart Parking Sensor using Arduino

## 📌 Project Description

This project is an Arduino-based smart parking sensor designed to detect the distance of a vehicle from a parking area.

An ultrasonic distance sensor measures the distance between the vehicle and the sensor. Based on the detected distance, the system provides visual and audio alerts using LEDs and a buzzer.

## 🛠️ Components Used

- Arduino Uno
- Ultrasonic Distance Sensor
- Red LED
- Yellow LED
- Green LED
- 220Ω Resistors
- Buzzer
- Jumper Wires

## ⚙️ Working

The ultrasonic sensor continuously measures the distance.

- 🟢 More than 30 cm → Parking area is clear
- 🟡 10–30 cm → Vehicle is nearby
- 🔴 Less than 10 cm → Vehicle is very close and buzzer turns ON

## 🔌 Pin Connections

| Component | Arduino Pin |
|---|---|
| Ultrasonic TRIG | D7 |
| Ultrasonic ECHO | D6 |
| Green LED | D8 |
| Yellow LED | D9 |
| Red LED | D10 |
| Buzzer | D11 |

## 💻 Programming

The project is programmed using Arduino C/C++.

## 🧪 Simulation

The project can be simulated using Tinkercad Circuits.

## 🎯 Objective

The objective is to demonstrate distance measurement, sensor interfacing, digital output control, and basic parking assistance using Arduino.

## 🚀 Future Improvements

- Add an LCD display
- Add multiple parking slots
- Add automatic parking-slot detection
- Add IoT monitoring using ESP32
- Develop a mobile application
