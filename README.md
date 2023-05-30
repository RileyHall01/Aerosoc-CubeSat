# Aerosoc-CubeSat
This repository contains all of the relevant technical files for
the UTS Aerosoc CubeSat project.

The cube-sat project consists of multiple STM32 32-bit Arm Cortex MCUs
that serve specific functions such as power management, RF communications,
data logging, and attitude control through a magnetorquer. These functions
are distributed across multiple PCBs to ensure efficient operation.

To achieve the desired functionality, each MCU needs to be programmed to
control GPIO pins, which enable the toggling of sensors and other
components. Additionally, the microcontrollers are responsible for
performing calculations related to the solar tracker, magnetorquer, and
compression/transfer functions for data transmission/reception via radio
communications.

Through software programming, the microcontrollers can interface with
various sensors, actuators, and communication modules. They collect data
from sensors, make decisions based on predefined algorithms, and send
commands to control the corresponding components. The software is
responsible for managing power resources efficiently, handling data
storage, processing, and compression, and implementing communication
protocols for reliable data exchange with ground stations.

The programming aspect involves developing firmware that runs on each
MCU, utilizing the appropriate libraries and frameworks to interact with
the hardware components. It requires writing code to configure and control
GPIO pins, read sensor data, perform calculations, handle interrupts,
implement communication protocols, and manage power modes effectively.

Overall, the software development for the cube-sat project involves
designing and implementing the necessary algorithms, control logic, and
communication protocols to ensure proper functionality and coordination
of the various subsystems. Please note that this outline will certainly
change with time as the scope of the project expands.

Note: This project will be programmed in C++.
