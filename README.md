Inertial Measurement Unit (IMU) & Microcontroller Data Logger

This project showcases a complete hardware and firmware design developed entirely in Altium Designer. It integrates an STM32F4 microcontroller with an MPU-6050 6-axis IMU to acquire and process real-time motion data. The board is USB-powered, making it a portable and versatile embedded solution.

Applications include motion tracking for balancing robots, quadcopters, and autonomous vehicles. The design demonstrates skills in PCB design, impedance control, embedded programming, and power management — covering the full journey from concept to implementation.

🔑 Key Features

PCB Design & Prototyping

Designed full schematics and a 1.6 mm, 4-layer controlled-impedance PCB (JLCPCB specs).

Ensured high-speed USB signal integrity with controlled routing.

Impedance Control

Applied transmission line theory to achieve precise 90Ω impedance for USB differential pairs.

Embedded Firmware (C/C++)

Programmed STM32F4 for I²C communication with MPU-6050.

Implemented raw data acquisition from accelerometer and gyroscope.

Power Management

Designed LDO-based supply converting 5V USB to 3.3V.

Provided stable and noise-free power for reliable system operation.

📌 Skills Demonstrated

PCB design in Altium Designer

High-speed interface layout and impedance control

Embedded C/C++ programming for microcontrollers

Sensor integration and data acquisition

Power supply design and regulation
