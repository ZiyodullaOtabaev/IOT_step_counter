# ESP32 IoT Step Counter Using MPU6050

## 📌 Project Overview
This project implements an IoT-based step counter (pedometer) using an ESP32 microcontroller and an MPU6050 accelerometer. The system detects human walking motion by analyzing acceleration data and displays the step count on a 0.91-inch OLED display. The project is suitable for wearable and health-monitoring applications.

---

## 🎯 Objectives
- To measure human steps using motion sensing
- To interface MPU6050 with ESP32 using I2C
- To implement a software-based step detection algorithm
- To display real-time step count on an OLED display
- To design a low-cost, portable pedometer system

---

## 🧩 Components Used
- ESP32 Development Board
- MPU6050 Accelerometer & Gyroscope
- OLED Display (0.91", 128×64, SSD1306)
- Push Button (Reset)
- 3.7V Lithium-ion Battery
- Slide Switch
- PCB (7×9 cm)
- Connecting wires

---

## 🔧 Working Principle
The MPU6050 measures acceleration along X, Y, and Z axes. The ESP32 calculates the magnitude of acceleration and compares it with a predefined threshold. When the threshold is crossed, a step is detected. A delay is applied to prevent false counts. The total number of steps is displayed on the OLED and printed to the serial monitor.

---

## 🔌 Wiring Connections

### MPU6050 → ESP32
| MPU6050 | ESP32 |
|------|------|
| VCC | 3.3V |
| GND | GND |
| SDA | GPIO 21 |
| SCL | GPIO 22 |

### OLED → ESP32
| OLED | ESP32 |
|------|------|
| VCC | 3.3V |
| GND | GND |
| SDA | GPIO 21 |
| SCL | GPIO 22 |

### Push Button
- One terminal → GPIO 23  
- Other terminal → GND  

---

## 💻 Software Used
- Arduino IDE
- ESP32 Board Package
- Adafruit MPU6050 Library
- Adafruit SSD1306 Library
- Adafruit GFX Library

---

## 🚀 Applications
- Fitness tracking devices
- Wearable electronics
- Health monitoring systems
- Activity tracking for elderly people

---

## 📸 Wiring Diagram
Add your wiring diagram image in the `images/` folder and reference it here.

---

## 📄 License
This project is for educational use.

## Acknowledgements

 - [Awesome Readme Templates](https://how2electronics.com/diy-pedometer-with-esp32-bmi160-steps-counter/)


## Authors

- [@ZiyodullaOtabayev](https://www.github.com/ZiyodullaOtaboyev)

