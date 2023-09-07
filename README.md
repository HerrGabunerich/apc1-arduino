# ScioSense APC1 Arduino Library
the Arduino library for the Air Purification Combo ONE (APC1) sensor with UART or I2C interface from ScioSense.

<img src="images/apc1.png" width="400">

The APC1 is a compact, box-shaped, all-in-one environmental sensor solution produced by
[ScioSense](http://www.sciosense.com) to precisely
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
* [Further information about the APC1](https://www.sciosense.com/products/environmental-sensors/apc1/)  
* [Datasheet](https://www.sciosense.com/wp-content/uploads/documents/SC-001581-DS-4-APC1-Datasheet.pdf)
* Buy the APC1 on [Mouser](https://mou.sr/3RccQwh) or [Digikey](https://www.digikey.nl/short/2v43qfh4)
 
## Prerequisites
It is assumed that
 - The Arduino IDE has been installed.
   If not, refer to "Install the Arduino Desktop IDE" on the
   [Arduino site](https://www.arduino.cc/en/Guide/HomePage).
 - Install your board. This library was tested with the ESP32. Here is a step-by-step guide for board installation 
(coming soon).


## Installation

### Installation via Arduino Library Manager (coming soon)
- In the Arduino IDE, navigate to the Arduino Library Manager on the left side (or, alternatively, select Sketch > 
Include Library > Manage Libraries...)
- Search for `ScioSense_APC1`
- Select the library from the search results and press `Install`

### Manual installation
- Download the code from this repository via "Download ZIP".
- In Arduino IDE, select Sketch > Include Library > Add .ZIP library... and browse to the just downloaded ZIP file.
- When the IDE is ready this README.md should be located at `C:\Users\[your_username]\Documents\Arduino\libraries\ScioSense_APC1\README.md`.


## Wiring

### General
Please make sure that you use the correct supply voltage: The APC1 runs at VDD = 5.0 V.

### Example with ESP32 (I2C)
This example shows how to wire a [ESP32DevKitC](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/hw-reference/esp32/get-started-devkitc.html#get-started-esp32-devkitc-board-front) 
with the APC1 for I2C communication.

| ENS21x flex foil | ESP32 |
|:----------------:|:-----:|
|       VDD        |  5V   |
|       GND        |  GND  |
|       SDA        |  G21  |
|       SCL        |  G22  |

<img src="images/i2c_pinout_esp32.png" width="1000">

## Build an example
To build an example sketch
 - (Re)start Arduino.
 - Open File > Examples > Examples from Custom Libraries > ScioSense_APC1 > 01_Basic (or any other of the provided 
examples you wish to run)
 - Make sure Tools > Board lists the correct board.
 - Select Sketch > Verify/Compile.

## Contributing
Contributions in the form of issue opening or creating pull requests are very welcome!

## Acknowledgements
This library is developed for ScioSense by [at² GmbH](https://www.at2-software.com/en/) 

@at2software

### ScioSense is a Joint Venture of ams AG 
