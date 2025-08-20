# KGP_4x2209
![KGP_4x2209 Elevation](https://github.com/3dApothecary-xyz/KGP_4x2209/blob/main/Images/KGP_4x2209-Rev_7-Elevation.png)

## The KGP_4x2209 is a complete, cost effective, easy to use 3D printer main controller board for beginners and experts

Designed for Klipper, the KGP_4x2209 is fast to set up and simple to wire into an existing 3D printer chassis or a new one.  The Raspberry Pi CM4, or equivalent, Single Board Computer (SBC) sockets provide a one-stop host connection between the main controller board and the host that includes the USB connection, power as well as commonly used Raspberry Pi peripherals including additional USB 2.0 sockets, Ethernet connection, HDMI output, CSI and DSI connectors as well as the standard 40 pin Raspberry Pi IO connector.  As a Klipper main contorller board, the KGP_4x2209 is well featured with all of the most used standard 3D printer peripherals as well a CAN port for implementing toolhead controllers.  The KGP_4x2209 is the best designed and most capable 3D printer main controller board available.  

The KGP_4x2209 was designed with an eye towards making its set up and operation as fast and intuitive as possible.  Connectors are color coded as well as being horizontal, giving clear access to the pin information on the PCB silkscreen as well as the many indicator LEDs.  Electrically, peripheral functions are designed to be "orthogonal" which means they are not set for predetermined functions - for example, the stepper motor drivers can be used for any of the axes or the extruder and the heater outputs are designed for bed heaters (not a single bed heater and extruder heater).  The KGP_4x2209 is designed for simplified power wiring with having the host built into the PCB and CAN power provided in the standard Microfit connector.  The positioning of connectors was done in mind of user needs, not the convenience of the board designer.  With mounting holes placed at the board corners, not interfering with connector, the KGP_4x2209 was designed by 3D printer enthusiasts for 3D printer enthusiasts to get the printers up and running as quicking and easily as possible.  

![KGP_4x2209-Operating](https://github.com/3dApothecary-xyz/KGP_4x2209/blob/main/Images/KGP_4x2209-Operating.jpg)

## User Manual

[User Manual](documentation/UserManual.pdf)

## Technical information for the KGP 4x2209 3D Printer Main Controller Board

### Targeted Printer Archtectures
* Traditional cartesian 
* Bedslingers with and without Z-Tilt (Z-Tilt will require a toolhead controller connected by CAN)
* CoreXY (without Quad Gantry Level)
* Delta

### STM32G0B1 MCU
* 64MHz Operating Speed
* DFU Mode Programming
* Katapult Programming
* USB Connection to Host

### Raspberry Pi CM4 (or equivalent) Host Socket
* 5A current supply for host (Supports Raspberry Pi CM5 and other, high current draw SBCs)
* Micro SD Card for Operating System/File System Storage (32GB+ recommended)
* Open PCB area for best internal Raspberry Pi CM4/CM5 WiFi antenna operation
* RJ45 Ethernet connector
* 2x USB 2.0cConnectors
* Full sized HDMI connector
* CSI/DSI connectors
* 40 Pin standard Raspberry Pi header

### 3D Printer Interfaces
* DFU/Reset buttons with indicator LEDs
* 4x TMC2209 stepper motor drivers each with serial "DIAG" pin connection
* 5x 3Pin yellow endstop connectors with yellow indicator LEDs
* 3Pin header for inductive sensors using input Voltage with yellow indicator LED
* 2x 15A screw termainal heater connectors with red indicator LEDs
* 2x 2Pin red NTC thermistor connectors with 4.7k pull up resistors
* 4x 2Pin white fan/LED strip connectors with blue indicator LEDs
* CAN Interface with split 60Ω termination
* "EXP1"/"EXP2" headers with wiring for UC1701 user interface
* 6Pin SPI header for ADXL345 with OR gate protection on MOSI/SCL pin
* 5Pin BL Touch header with yellow indicator LED
* 4Pin I2C header
* Input Voltage monitor

![KGP_4x2209 Topside](https://github.com/3dApothecary-xyz/KGP_4x2209/blob/main/Images/KGP_4x2209-Rev_7-Topside.png)

![KGP_4x2209 Backside](https://github.com/3dApothecary-xyz/KGP_4x2209/blob/main/Images/KGP_4x2209_Rev_7-Backside.png)
