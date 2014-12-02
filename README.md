swift01
=======

The software for Swiftlet Technology's Open-Source Wireless Mesh module implementing IEEE 802.15.5

The software is built in Atmel Studio 6.2 and makes use of many Atmel Software Framework libraries. The Code ought to be able to be compiled using GCC for ARM (Atmel Studio is based on arm-none-eabi) as Atmel Studio generates makefiles for the toolchain to consume.
To open the project, install Atmel Studio and open the file Swift01.atsln.

Hardare details are located here: http://swiftlet.technology/blog/2014/10/hardware-specifications/
Software generalities are located here: http://swiftlet.technology/blog/2014/11/module-software-approach/

The ASF libraries employed in this project are:
Generic board support
NVM - Non-volatile Memory Common API
EXTINT - External Interrupt
SERCOM USART - Serial Communications
SYSTEM - Core System Driver
Standard serial I/O (stdio)
FreeRTOS mini Real-Time Kernel 8.0.1
AVR2025 - IEEE 802.15.4 MAC v3.1.1
