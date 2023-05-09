# ScioSense APC1 
Arduino library for the APC1 sensor with UART or I2C interface from ScioSense.

## Introduction
This project is an Arduino *library*. It implements a driver with examples for the APC1.

The APC1 is a compact, box-shaped, all-in-one environmental sensor solution to precisely
measure particulate matter and aerosols, volatile organic compounds, temperature and
humidity. It leverages the ScioSense leading edge sensor technology to provide an
accurate, fully calibrated, maintenance-free solution to air quality monitoring.

For maximum flexibility, the APC1 provides up to 20 environmental signal parameters
through UART or I2C interfaces. Moreover, it features temperature compensation
algorithms to simplify integration on system level, thereby accelerating time to market at
minimal overall BOM costs.

The APC1 is a proven, maintenance-free technology, designed for high volumes and
reliability.

## Links
The APC1 sensors are made by [ScioSense](http://www.sciosense.com).
 - In the library, an implementation for the APC1 is given. The datasheet and further documents for this sensor can be downloaded here
   https://www.sciosense.com/products/environmental-sensors/apc1/
   
## Prerequisites
It is assumed that
 - The Arduino IDE has been installed.
   If not, refer to "Install the Arduino Desktop IDE" on the
   [Arduino site](https://www.arduino.cc/en/Guide/HomePage).
 - The library directory is at its default location.
   For me, that is `C:\Users\sciosense\Documents\Arduino\libraries`.

## Installation

### Installation via Arduino Library Manager
- In the Arduino IDE, navigate to the Arduino Library Manager on the left side (or, alternatively, select Sketch > Include Library > Manage Libraries...)
- Search for `ScioSense_APC1_Arduino_Library`
- Select the library from the search results and press `Install`

### Manual installation
- Download the code from this repo via Download ZIP.
- In Arduino IDE, select Sketch > Include Library > Add .ZIP library... and browse to the just downloaded ZIP file.
- When the IDE is ready this README.md should be located at e.g. `C:\Users\sciosense\Documents\Arduino\libraries\ScioSense_APC1_Arduino_Library\README.md`.

## Build an example
To build an example sketch
 - (Re)start Arduino.
 - Open File > Examples > Examples from Custom Libraries > ScioSense APC1 > 01_SoftwareSerial (or any other of the provided examples you wish to run)
 - Make sure Tools > Board lists the correct board.
 - Select Sketch > Verify/Compile.

## Acknowledgements
This library is developed for ScioSense by [at² GmbH](https://www.at2-software.com/en/) 

@at2software

 
### ScioSense is a Joint Venture of ams AG 