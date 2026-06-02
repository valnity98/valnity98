# Mutasem Bader — Robotics & Embedded Systems Engineer

**M.Sc. Mechatronics & Robotics** · Frankfurt University of Applied Sciences

Passionate about building complete systems: from bare-metal embedded firmware and real-time operating systems to computer vision pipelines and robot autonomy. I work across the full stack — STM32 firmware in C, ROS 2 nodes in Python, TinyML deployment with X-CUBE-AI, and custom PCB design.

---

## Skills

### Embedded Systems
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-green?style=flat)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat&logo=arduino&logoColor=white)

**Peripherals:** DCMI · DMA · UART · I²C · SPI · CAN Bus  
**Tools:** STM32CubeIDE · STM32CubeMX · X-CUBE-AI · MATLAB/Simulink · KiCad / EasyEDA

### Robotics & ROS 2
![ROS2](https://img.shields.io/badge/ROS_2-22314E?style=flat&logo=ros&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

**Topics:** Mobile robot control · Encoder odometry · PID control · Camera-based line following · TF2 · OccupancyGrid mapping

### Machine Learning / Edge AI
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![TFLite](https://img.shields.io/badge/TFLite-FF6F00?style=flat)

**Topics:** TinyML · MobileNet · Post-training quantisation (PTQ) · On-device inference · ST Model Zoo

---

## Featured Projects

### [Machine Vision on Microcontrollers](https://github.com/valnity98/Machine-Vision-on-Microcontrollers)
> STM32H7 · FreeRTOS · OV2640 · X-CUBE-AI · PySide6

Real-time edge vision system on STM32H743ZI. Classical CV pipeline (Otsu threshold, morphology, run-length CCL) and TinyML object counting (MobileNetV1-0.25, 96×96 RGB, 5 classes) — **all inference on-chip**. PySide6 dashboard for control, benchmarking and dataset capture. Full ML training pipeline (TensorFlow → TFLite PTQ → X-CUBE-AI deployment).

---

### [ZumoRobot-ROS 2](https://github.com/valnity98/ZumoRobot-ROS2)
> ROS 2 · Python · OpenCV · FreeRTOS · PID control · Dead-reckoning

Autonomous line-following and path-mapping for a Zumo robot. Camera-based line detection with Kalman filter, PID motor control over serial, encoder-based dead-reckoning odometry, TF2 broadcasting, OccupancyGrid mapping, and a PyQt5 live dashboard.

---

### [Zumo328P Arduino Library](https://github.com/valnity98/Zumo328P-Library)
> C++ · ATmega328P · Interrupt-driven encoder · PID

Ported the Pololu Zumo 32U4 encoder library to the ATmega328P (Arduino Uno). Software-based XOR replacement for quadrature decoding with `attachInterrupt()`, signed 32-bit atomic tick counters, and a discrete-time PID motor controller.

---

### [Instrument Cluster — CAN Bus Simulation](https://github.com/valnity98/Instrument-Cluster)
> MATLAB/Simulink · CAN Bus · Vehicle Network Toolbox · DBC

MATLAB/Simulink simulation of CAN messages for a BMW E9x instrument cluster. Custom DBC file, signal generation, and hardware-in-the-loop testing via the Vehicle Network Toolbox.

---

### [PID Demonstrator — STM32 PCB](https://github.com/valnity98/PID-Demonstrator)
> STM32F4 · PCB Design · DRV8848 · INA138 · MATLAB PID Tuner

Custom PCB for a real-time PID demonstrator: STM32F4-Discovery as controller, DRV8848 H-bridge, INA138 current sensing, voltage regulation (12 V → 3.3 V), and hardware-adjustable Kp/Ki/Kd via potentiometers. PID parameters tuned with MATLAB PID Tuner.

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](www.linkedin.com/in/mutasem-bader-128442285)
[![GitHub](https://img.shields.io/badge/GitHub-valnity98-181717?style=flat&logo=github)](https://github.com/valnity98)
[![Email](https://img.shields.io/badge/Email-m.bader98%40outlook.de-D14836?style=flat&logo=gmail&logoColor=white)](m.bader98@outlook.de)

📍 Frankfurt am Main, Germany
