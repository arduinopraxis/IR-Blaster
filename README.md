# IR-Blaster

The IR Blaster is a simple IR sender module with an onbloard ESP8266 microcontroller board.
You can controll RGB LED stripes or a TV with the IR Blaster and a smartphone or tablet.

This smartphone project is published in my Book "Heimautomation mit Arduino, ESP8266 und Raspberry Pi, ISBN: 9783958456716"
https://www.mitp.de/IT-WEB/Elektronik-Maker/Heimautomation-mit-Arduino-ESP8266-und-Raspberry-Pi.html

## Application
Application with webinterface via Node-RED

## Microcontroller
Wemos D1 Mini

## Circuit Diagram
![tb_project_ir_blaster_maxi_wemos_revA_sch](https://user-images.githubusercontent.com/913135/118676066-6428c580-b7fb-11eb-89bd-75605dbee1e8.jpg)

## PCB
![tb_project_ir_blaster_maxi_wemos_revA_brd](https://user-images.githubusercontent.com/913135/118676426-afdb6f00-b7fb-11eb-9202-50c6b955a3df.jpg)

## Firmware Wemos D1 Mini
tasmota-sensors.bin 
see https://github.com/arendst/Tasmota/releases/


## BOM
- 1 PCB (IR Blaster Maxi Wemos, Rev.A)
- 2 Headers 1x8pin (for Wemos D1 Mini)
- 7 Transistor BC846 SMD (T1 - T7)
- 7 Resistor SMD 1206 100 R (R4, R5, R6, R10, R11, R12, R13)
- 7 Resistor SMD 1206 1k (R1, R2, R3, R7, R8, R9, R14)
- 7 IR LED TSUS 5400 TEL 950nm (LED1 - LED7)

## Case
see https://www.thingiverse.com/thing:2412098

