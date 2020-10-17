# STM8S001J3 tiny board

![Front view](docs/STM8S001J3_tiny_board_front.jpg)

A tiny dev board for [STM8S001J3](https://www.st.com/en/microcontrollers-microprocessors/stm8s001j3.html) MCU designed in KiCad. 

The board has the LED (D1) that is connected to pin #1 of the MCU and two (optional) pull-up resistors for the I²C bus.

## Pinout

Left connector | Right connector
--- | ---
SWIM | PA1, PD6, LED
VDD | PC3, PC4, PC5
VDD | PB4, I2C SCL
GND | PA3, PB5, I2C SDA

> *seen from the front*

## Components

Name | Value | Notes
--- | --- | ---
U1 | STM8S001J3 |
C1 | 1µF |
C2 | 100nF |
C3 | 1µF | VCAP
D1 | LED |
R1 | 2K |
R2 | 4.7K | *optional, I2C pull-up*
R3 | 4.7K | *optional, I2C pull-up*

Components size: SMD 0603

## License
This project is licensed under the MIT License - see the [LICENSE](/master/LICENSE) file for details.