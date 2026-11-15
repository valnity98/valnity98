# Mutasem Bader

Master's student in Mechatronics and Robotics at Frankfurt University of Applied Sciences, graduating in 12/2026.

I work close to the hardware: from the schematic and the PCB through C/C++ firmware to the analysis of the measured data. My three focus areas are embedded development, measurement and test technology, and control and robotics.

**Right now:** master's thesis at IoT Venture GmbH in Darmstadt. I write firmware for a bike tracker (nRF52840, Zephyr RTOS, IMU, SD card logging, BLE) and analyse recorded rides with Python to detect events. It is a company project, so the code is not public.

**Looking for:** a full-time entry-level position from January 2027 in embedded software and firmware, test and measurement systems, or control and robotics. Rhine-Main and Rhine-Neckar area.

## Projects

### [Machine Vision on Microcontrollers](https://github.com/valnity98/Machine-Vision-on-Microcontrollers)

Object counting on an STM32H743 with an OV2640 camera, done in two ways on the chip itself: classical image processing and a quantised MobileNetV1 (TinyML, deployed with X-CUBE-AI). Firmware in C on FreeRTOS, with a PC dashboard in Python for control and benchmarking. Tested on a series of 90 images under changing light, about 60 ms per inference. Course project, grade 1.0.

### [ZumoRobot-ROS2](https://github.com/valnity98/ZumoRobot-ROS2)

A line-following robot with ROS 2 that also maps the path it has driven. I wrote the nodes for PID motor control, encoder odometry and path mapping, the Qt interface, and put the system together. A teammate did the image processing. Team project.

### [Zumo328P Library](https://github.com/valnity98/Zumo328P-Library)

Arduino library for the wheel encoders of the Zumo Shield on an Arduino Leonardo. I ported it from Pololu's Zumo 32U4 library (interrupt-driven counting on channel A, direction from channel B) and added a PD controller for steering.

### [Instrument Cluster: CAN Bus Control](https://github.com/valnity98/Instrument-Cluster)

Driving a real BMW E9x instrument cluster over CAN with MATLAB/Simulink and a DBC file. Engine speed, vehicle speed, turn signals and ignition terminals are displayed correctly. Team project.

### [PID Demonstrator](https://github.com/valnity98/PID-Demonstrator)

Hardware concept and PCB for an STM32F4 control loop with a DRV8848 H-bridge, INA138 current sensing and USB-C Power Delivery. Designed, built and tested. Team project.

## Experience

| Period | Where and what |
|---|---|
| 07/2026 to 12/2026 | **IoT Venture GmbH**, Darmstadt. Master's thesis: embedded firmware and data analysis |
| 04/2025 to 02/2026 | **Löwenstein Medical Innovation**, Steinbach. Working student in advanced development: requirements, architecture and a Simulink model for a lung simulator |
| 10/2024 to 02/2025 | **Frankfurt UAS**. Tutor in the STM32 microcontroller lab |
| 09/2022 to 05/2024 | **tecsis GmbH (WIKA Group)**, Offenbach. Internship, working student and bachelor's thesis (grade 1.1): automated test system with my own PCB and LabVIEW software |

## Skills

- **Programming:** C, C++, Python, MATLAB/Simulink, LabVIEW
- **Embedded:** Zephyr RTOS (nRF Connect SDK), FreeRTOS, nRF52840, STM32, Arduino
- **Interfaces:** BLE, CAN, I²C, SPI, UART, RS232 (SCPI, VISA), Ethernet (lwIP)
- **Vision, robotics, ML:** ROS 2, OpenCV, TinyML (TensorFlow Lite, X-CUBE-AI), scikit-learn
- **Hardware:** schematic and PCB design (Eagle, Fusion 360), enclosure design (Creo, SolidWorks)
- **Tools:** Git/GitLab, Jira, UML

## Languages

German (C1), English (B2), Arabic (native)

## Contact

- LinkedIn: [mutasem-bader-128442285](https://www.linkedin.com/in/mutasem-bader-128442285)
- Email: [m.bader98@outlook.de](mailto:m.bader98@outlook.de)
- Frankfurt am Main, Germany
