# VSD_FPGA_Workshop
Project 1: FPGA VDI Installation
Description
This project guides users through setting up a Virtual Desktop Infrastructure (VDI) tailored for FPGA development, ensuring a consistent and efficient development environment.

Features
Pre-configured FPGA development tools
Remote access to development environments
Scalable setup for multiple users

Requirements
VSDSquadron FPGA Mini board
Stable internet connection
Access credentials for the VDI platform

Usage
Access the VDI platform using provided credentials.
Navigate to the FPGA development environment.
Begin your development using the pre-installed tools.

Project 2: LED Blinking and UART Loopback
Description
A foundational project that introduces users to basic FPGA operations by implementing an LED blinking sequence and setting up a UART loopback for serial communication testing.

Features
Configurable LED blinking patterns
UART loopback for testing serial communication
Real-time feedback via serial monitor

Requirements
VSDSquadron FPGA Mini board
USB-C cable for power and programming

Usage
Connect the FPGA Mini board to your PC via USB-C.
Upload the LED blinking and UART loopback firmware.
Open the serial terminal to monitor UART communication.

Project 3: Real-time Sensor Data Acquisition
Description
This project demonstrates the FPGA Mini's capability to interface with various sensors, acquiring and processing data in real-time for applications like environmental monitoring.

Features
Support for multiple sensors (e.g., temperature, humidity)
Real-time data acquisition and processing
Data visualization via serial output

Requirements
VSDSquadron FPGA Mini board
Compatible sensors (e.g., DHT11, LM35)
Breadboard and jumper wires

Usage
Connect sensors to the FPGA Mini using the breadboard.
Upload the sensor data acquisition firmware.
Monitor real-time sensor data via the serial terminal.

Project 4: RISC-V Implementation on FPGA
Description
A comprehensive project that involves implementing a RISC-V processor core on the FPGA Mini, enabling users to understand processor architecture and instruction execution.

Features
32-bit RISC-V core implementation
Execution of basic instructions
Integration with peripherals for I/O operations

Requirements
VSDSquadron FPGA Mini board
RISC-V toolchain
USB-C cable for programming

Usage
Set up the RISC-V development environment.
Synthesize and upload the RISC-V core to the FPGA Mini.
Run test programs to validate the implementation.

About VSDSquadron FPGA Mini
The VSDSquadron FPGA Mini is a compact and affordable development board designed for learners and professionals to explore FPGA and RISC-V based projects.

Key Features
Powered by CH32V003F4U6 chip with 32-bit RISC-V core
Operates at 24MHz system frequency
Equipped with 16KB Flash and 2KB SRAM
Provides 15 GPIO pins for versatile interfacing
Supports USART, I2C, and SPI communication protocols
On-board programmer eliminates the need for external programming devices

We followed the common commands:
sudo make
sudo build
sudo make flash
sudo make terminal
By- Gagandeep Cholaki
