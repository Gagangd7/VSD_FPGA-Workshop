# VSD_FPGA-Workshop
1) Description
This project demonstrates a simple LED blinking application using the VSD Squadron development board. The VSD Squadron is a custom-designed microcontroller development board based on FPGA SoC. This example toggles onboard LEDs at regular intervals to showcase basic GPIO control and timing.

2) Features
Blinks onboard user LEDs at a fixed rate
Written in verilog and compiled using the VSDOpen GCC RISC-V toolchain
Deployed on the VSD Squadron FPGA-based board
Demonstrates basic GPIO manipulation and delay handling

3) Usage
Connect your VSD Squadron board to your system via USB.
Open your preferred RISC-V toolchain environment (e.g., VSDOpen).
Compile the code using make or your build script.
Flash the binary to the board using the UART interface or SPI programmer.
Observe the LED blinking pattern on the board.

4) Requirements
VSD Squadron board (with onboard VSDOpen™ FPGA)
GCC toolchain
UART/SPI programmer or onboard USB interface
VSDOpen software toolchain or compatible open-source tools

Notes
Refer to the VSD Squadron Datasheet for pinout and LED specifications.
Ensure the power supply to the board is stable before programming.

By- Gagandeep S C
