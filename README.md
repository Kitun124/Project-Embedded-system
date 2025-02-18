# Project-Embedded-system
# RFID Reader
# Component
## Requirement
|**Component**|**Specification**|**Reason**|
| --- | --- | --- |
| Microcontroller | STM32F103C8T6 "Blue Pill" | Fast SPI support;Low power consumption;Multiple peripherals (I2C, UART, GPIO, ADC);Affordable & widely supported |
| RFID Module (RC522) | Use to read cards for door | Cheap & widely available;Works at 3.3V;ompatible with STM32;Fast SPI communication;Supports MIFARE 13.56 MHz cards |
| LCD 16x2 | Show status | Simple & widely supported ;Low power consumption (runs on 3.3V or 5V);Easy interface options |
| Breadboard | Act as PCB to store the whole circuit |Easy prototyping & testing (no soldering);Saves time & cost before making a PCB; Easy debugging & modifications; Modular & reusable for other projects |
| Buzzer | Sounds alarm | Loud & Clear Sound; Better Compatibility; Simple Control STM32 |
| Motor | Act as door ( rotate = open, not= close) | Compact and Lightweight; Low Power Consumption;Ease of Control; Cost-Effective; Reliability |
|Motor Driver ( L298 DC) | To control the motor | Simple Integration; Dual Motor Control; Speed Control; Direction Control; Affordable; Reliable and Tested|
