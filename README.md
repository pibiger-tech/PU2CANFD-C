# Pibiger SavvyCAN Series Products
Pibiger SavvyCAN Series Products are SocketCAN devices which is free to use under linux.

## About Hardware
- [Hardware Manual](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FkOVFVvzO53fwzjprHC3b%2Fuploads%2FG7i2LkR2aBygXF3vV7FH%2FSavvyCAN%20Hardware%20Manual.pdf?alt=media&token=150d36e2-53db-464f-9ff7-b4dd215a8bb9"Hardware_Manual")
## About SavvyCAN
SavvyCAN is a cross platform QT based C++ program. It is a CAN bus reverse engineering and capture tool. It was originally written to utilize EVTV hardware such as the EVTVDue and CANDue hardware. It has since expanded to be able to use any socketCAN compatible device as well as the Macchina M2 and Teensy 3.x boards. SavvyCAN can use any CAN interface supported by QT's SerialBus system (PeakCAN, Vector, SocketCAN, J2534, etc) It can capture and send to multiple buses and CAN capture devices at once.
It has many functions specifically meant for reverse engineering data found on the CAN bus:
- Ability to capture even very highly loaded buses
- Ability to connect to many dongles simultaneously
- Scan captured traffic for data that looks coherent
- Show ASCII of captured data to find things like VIN numbers and traffic to and from the radio
- Graph data found on the bus
- Load and Save many different file formats common to CAN capture tools (Vector captures, Microchip, CANDo, PCAN, and many more)
- Load and Save DBC files. DBC files are used to store definitions for how data are formatted on the bus. You can turn the raw data into things like a RPM, odometer readings, and more.
- UDS scanning and decoding
- Scripting interface to be able to expand the scope of the software
- Best of all, it's free and open source. Don't like something about it? Change it!

## Software
* MacOs:https://github.com/collin80/SavvyCAN/releases/download/V208/SavvyCAN.dmg
* Linux: https://github.com/collin80/SavvyCAN/releases/download/V208/SavvyCAN-x86_64.AppImage
* Windows: https://github.com/collin80/SavvyCAN/releases/download/V208/SavvyCAN_CIBuild.zip

## Driver
- Plug And Play Under Linux 

## More information
- https://www.savvycan.com/
- https://www.savvycan.com/docs/
- https://github.com/collin80/SavvyCAN

## Third Party Windows Software
The following software and drivers are provided by third parties and are for testing use only,Please do not use for commercial purpose, we are not responsible for the following resources:
- [Driver](https://2214540728-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fc9gHV3stj5J1Ngg514P3%2Fuploads%2FUyljf23EipSyIKCzDi6F%2FDriver.zip?alt=media&token=ac1d46af-f95f-45f2-8995-8e88e9a22c85 "Driver")
- [Busmaster](https://rbei-etas.github.io/busmaster/ "Busmaster")