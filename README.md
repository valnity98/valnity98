# Mutasem Bader — Embedded Software & Edge-AI Engineer

**M.Sc. Mechatronics & Robotics** (expected 12/2026) · Frankfurt University of Applied Sciences

I build embedded systems end to end, from the PCB to the firmware to the data coming out of it. Most of my work is C on nRF52 and STM32 (Zephyr, FreeRTOS), Python for ROS 2 and ML tooling, and TinyML with X-CUBE-AI.

**Currently:** Master's thesis at IoT Venture GmbH: firmware (nRF52840, Zephyr RTOS, IMU, BLE, SD logging) and a machine-learning pipeline for data-driven event detection in a connected bike tracker. Company project, so no code is published here.

**Open to:** full-time roles in Embedded Software / Firmware and Edge-AI from **January 2027** (Rhine-Main area or remote).

---

## Skills

### Embedded Systems
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![Zephyr](https://img.shields.io/badge/Zephyr_RTOS-7929D2?style=flat&logo=zephyrproject&logoColor=white)
![nRF52](https://img.shields.io/badge/Nordic_nRF52-00A9CE?style=flat&logo=nordicsemiconductor&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-green?style=flat)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat&logo=arduino&logoColor=white)

**Peripherals & protocols:** DCMI · DMA · UART · I²C · SPI · CAN Bus · BLE  
**Tools:** nRF Connect SDK / west · STM32CubeIDE · STM32CubeMX · X-CUBE-AI · MATLAB/Simulink · Autodesk Fusion / Eagle

### Robotics & ROS 2
![ROS2](https://img.shields.io/badge/ROS_2-22314E?style=flat&logo=ros&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

**Topics:** Mobile robot control · Encoder odometry · PID control · Camera-based line following (team project) · TF2 · OccupancyGrid mapping

### Machine Learning / Edge AI
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![TFLite](https://img.shields.io/badge/TFLite-FF6F00?style=flat)

**Topics:** TinyML · MobileNet · IMU feature engineering · Random Forest (scikit-learn) · Post-training quantisation (PTQ) · On-device inference · ST Model Zoo

---

## Featured Projects

### [Machine Vision on Microcontrollers](https://github.com/valnity98/Machine-Vision-on-Microcontrollers)
> STM32H7 · FreeRTOS · OV2640 · X-CUBE-AI · PySide6

Object counting on an STM32H743ZI, compared two ways, both running on the chip: classical image processing (Otsu threshold, morphology, connected components) and a quantised TinyML model (MobileNetV1-0.25, 96×96 RGB, 279 KB Flash / 57 KB RAM). On 90 real-world test frames with changing light, TinyML reached **73.3 %** accuracy and the classical pipeline **14.4 %** (measured with a firmware version that has a known Otsu overflow bug, so this value is not a limit of the method and has not been re-measured); inference takes 59.8 ms vs. 66.6 ms. Course project (grade 1.0); the PySide6 PC dashboard was written with AI assistance.

---

### [ZumoRobot-ROS 2](https://github.com/valnity98/ZumoRobot-ROS2) · team project
> ROS 2 · Python · OpenCV · PID control · Dead-reckoning

Autonomous line-following and path-mapping for a Zumo robot. Camera-based line detection (team project; Kalman-filtered centroid in the debug overlay), PID motor control over serial, encoder-based dead-reckoning odometry, TF2 broadcasting, OccupancyGrid mapping, and a PyQt5 live dashboard.

---

### [Zumo328P Arduino Library](https://github.com/valnity98/Zumo328P-Library)
> C++ · Arduino Leonardo (ATmega32U4) · Interrupt-driven encoder · PD controller

Ported the Pololu Zumo 32U4 encoder library (MIT licence) to the Zumo Shield with an Arduino Leonardo (ATmega32U4). Interrupt-driven quadrature decoding with `attachInterrupt()` (channel A edges, direction from channel B), signed 32-bit atomic tick counters, and a discrete-time PD steering controller.

---

### [Instrument Cluster — CAN Bus Control](https://github.com/valnity98/Instrument-Cluster) · team project
> MATLAB/Simulink · CAN Bus · Vehicle Network Toolbox · DBC

Controlling a real BMW E9x instrument cluster over CAN with MATLAB/Simulink. Custom DBC file, signal generation in Simulink, and validation on the real cluster via the Vehicle Network Toolbox (over 90 % of the signals displayed correctly).

---

### [PID Demonstrator — STM32 PCB](https://github.com/valnity98/PID-Demonstrator) · team project
> STM32F4 · PCB Design · DRV8848 · INA138 · MATLAB PID Tuner

Custom PCB for a real-time PID demonstrator: STM32F4-Discovery as controller, DRV8848 H-bridge, INA138 current sensing, USB-C Power Delivery input (12 V) with on-board step-down, and hardware-adjustable Kp/Ki/Kd via potentiometers. PCB v1 was built and tested; a revised v2 was designed but not manufactured. My part: hardware design and system integration; I supported the PID tuning with MATLAB PID Tuner.

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mutasem-bader-128442285)
[![GitHub](https://img.shields.io/badge/GitHub-valnity98-181717?style=flat&logo=github)](https://github.com/valnity98)
[![Email](https://img.shields.io/badge/Email-m.bader98%40outlook.de-D14836?style=flat&logo=gmail&logoColor=white)](mailto:m.bader98@outlook.de)

📍 Frankfurt am Main, Germany
