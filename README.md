Branch of the Adafruit_MAX31856 library 
https://github.com/adafruit/Adafruit_MAX31856

Modified by LPM 2017
Added FAULT checking to the main `readThermocoupleTemperature()` function so that
it automatically returns `nan` if there is a fault (rather than a bogus 
temperature value). 


-----------------------------------------------
This is the Adafruit MAX31856 Arduino Library 

Tested and works great with the Adafruit Thermocouple Breakout w/MAX31856
    
   * http://www.adafruit.com/products/xxxx

These sensors use SPI to communicate, 4 pins are required to  
interface

Adafruit invests time and resources providing this open source code, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Written by Limor Fried/Ladyada  for Adafruit Industries.  
BSD license, check license.txt for more information
All text above must be included in any redistribution