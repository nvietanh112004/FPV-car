# FPV Remote Controlled Car via WebSockets
![car1 png](https://github.com/user-attachments/assets/1ec44b00-cc1f-467b-ae7a-3528d46f1848)
## Overview
This project brings to life a functional FPV (First-Person View) robot car powered by the **ESP32-CAM**. It is capable of real-time video streaming and remote control via a web-based interface accessible from any device on your local network. The system allows you to steer the car, navigate obstacles, and monitor a live video feed with high responsiveness.

## Key Features
* **Real-Time Video Streaming**: Developed a streaming system using **ESP32-CAM** for low-latency **MJPEG** video transmission.
* **Low-Latency Control**: Achieved command latency of **under 50ms** by implementing the **WebSockets** protocol.
* **Precise Hardware Response**: 
    * Utilized **PWM (Pulse Width Modulation)** for smooth and precise DC motor speed control.
    * Optimized steering response via **interrupt-driven logic**.
* **Web-Based Interface**: A simple and intuitive UI to control the car and view the camera feed simultaneously.
* ![web png](https://github.com/user-attachments/assets/0cc2533a-1865-4c23-b29d-986d5be73aa3)

## Tech Stack
* **Programming**: C/C++.
* **Microcontroller**: ESP32-CAM.
* **Protocols**: WebSockets, MJPEG, PWM, GPIO.
* **Design Tools**: Altium Designer for Schematic & PCB Layout.
* **IDE**: VS Code / Arduino IDE.

## Components
* **ESP32-CAM**: The heart of the project, providing processing power and Wi-Fi connectivity.
* **L298N Motor Driver**: Responsible for controlling the motors and managing power distribution.
* **Custom 4-Wheel Robot Car**: The physical platform providing a sturdy base for the electronics.
* **Jumper Wires & Antenna**: For reliable hardware connections and stable signal range.

## Getting Started
To get started with this project, you’ll need the following:
1. An **ESP32-CAM** board and the components listed above.
2. **Arduino IDE** with the ESP32 core installed.
3. Flash the source code from `FPV-car.ino` to your board.


## <img width="1941" height="2049" alt="car2 png" src="https://github.com/user-attachments/assets/a9e190cd-1119-414e-95e9-96bca9e47699" />
Future Potential

This project is just the beginning. There’s room for numerous improvements and enhancements, including:

* **Autonomous Navigation**: Implementing computer vision or AI-based pathfinding to allow the car to navigate independently.
* **Sensor Integration**: Adding ultrasonic or LiDAR sensors for obstacle avoidance, similar to the data processing techniques used in my Air Quality Monitoring project.
* **UI Refinement**: Enhancing the web-based dashboard for a more immersive and feature-rich user experience.

I welcome contributions from anyone interested in taking this project further. Whether you’re looking to add features, optimize the code, or propose new ideas, your input is highly valued.

