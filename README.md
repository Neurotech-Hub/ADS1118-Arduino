# Arduino Library for Texas Instruments ADS1118 - 16-Bit Analog-to-Digital Converter with internal Reference and Temperature Sensor

This is an easy to use Arduino library for ADC Converter ADS1118, **Updated for SAMD21 chipsets**. Hard fork of [denkitronik/ADS1118: Arduino Library for Texas Instruments ADS1118 - 16-Bit Analog-to-Digital Converter with internal Reference and Temperature Sensor](https://github.com/denkitronik/ADS1118).

Note: SPI SCLK has been decreased for default compatibility with SPI isolator.

## Getting Started

Learn with the examples provided: For basic use "basicExampleAds1118" and "ads1118example" for a detailed use.

### Prerequisites

None

### Installing

Download this library as zip file, then click in "Sketch" -> "Include Library" ->"Add .ZIP Library" and select the zip file downloaded.

## Running the tests
1. Connect the ADS1118 in the 3.3v power supply pins of your Arduino.
2. Connect the ADS1118 CS pin to the pin 5 of your Arduino.
3. Connect the ADS1118 MISO (DOUT), MOSI(DIN) and SCLK pins to the MISO, MOSI and SCLK of your Arduino (search on internet "Arduino ICSP pinout").

|ARDUINO (ICSP PINS) |ADS1118 PINS |
| --- | --- |
| MOSI | DIN |
| MISO | DOUT |	
| SCLK | SCLK |
| 5 (change this pin to fit your needs) |CS |

4. Run the examples provided in your Arduino IDE. 
Go to "File" -> "Examples" -> "ADS1118 library" -> "basicExampleAds1118" or "ads1118example" 

## Built With
* [Arduino IDE](https://www.arduino.cc/)

## Authors
* **Alvaro Salazar** - *Initial work* - [alvaro-salazar](https://github.com/alvaro-salazar)
* **Matt Gaidica** - *Updated/tested with SAMD21 device* - [Neurotech Hub](https://github.com/Neurotech-Hub)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.
