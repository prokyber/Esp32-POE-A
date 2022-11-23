# greenPill
## Introduction:
Green pill is a low-cost development kit for nrf52840. The board supports programming via SWDIO and SWCLK pins using for example ST-LINK programmer.

## Features:

- NRF52840 chip
  - 64 MHz Cortex-M4 with FPU
  - 1 MB Flash, 256 KB RAM
  - 2.4 GHz Transceiver
  - 2 Mbps, 1 Mbps, Long Range
  - Bluetooth Low Energy, Bluetooth mesh
  - ANT, 802.15.4, Thread, Zigbee
- USB-C connector.
- Bluetooth SMD antenna.
- 33 GPIOs, 6 Analog Inputs(12 Bit), 4xPWM, Full-speed 12 Mbps USB,2xUART, 3xSPI(low speed), 1xSPI(high speed), 2xTWI, 1xPDM, 1xI2S, 1xQSPI. Most peripherals(like UART, TWI, SPI ...) can be mapped to any pin.
- External 32 Mhz and 32.768 kHz crystals.
- Accepts power through:
  - USB
  - External source (1.8V-5V)

## Pinout and dimensions
![pinout](pictures/pinoutV1.png)

![dimensions](pictures/dimensions.png)

## Programming options:
Using vscode Platformio and mbed/Arduino/Zephyr OS
1. Open vscode and Platformio extension. Create new project.
![platformio](pictures/platformio.png)

2. Choose NRF52-DK as a board. Choose your framework.
![createProject](pictures/createProject.png)

3. Write code, connect ST LINKV2 programmer, press ctrl-alt-u(upload) to compile and upload the code.

## Uploading example project:
For example projects go to https://github.com/allexoK/greenPillExamples

## Schematics
Schematics can be found in HW/schematics
# Esp32-POE-A
