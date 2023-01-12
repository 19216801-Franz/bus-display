# Bus trip display

This repository contains all files necessarry to build your own little bus trip display.

## Example build
![alt text](https://github.com/19216801-Franz/hafas-trip-display/blob/main/pictures/finished-example.jpg?raw=true)

## Instructions

* Set up your Arduino IDE to target the ESP8266. You'll have to install following libraries:
    * Adafruit GFX Library
    * ArduinoJSON
    * ArduinoSTL
    * EEPROM
    * ESP8266WebServer
* For my private project, I targeted the Hafas API of the public transportation for the northern-german state 'Schleswig-Holstein' nah-sh. Configure the station and API Endpoints to your needs. You can find more informations about available APIs in the project 'hafas-client', which features a collection of known endpoints:

 https://github.com/public-transport/hafas-client/tree/master/p

 If you change the API endpoint, make sure to also change the credentials used in the http body, according to the information in hafas-client.

* Print your display
* Assemble




## Parts you'll need
* ESP8266 NodeMCU V.1 board
* Waveshare 2.7 Inch E-Paper Display HAT (B)
* 7 M3 Screws + nuts
* Some cables
* Solder Equipment
* 3D Printer

## TODO:
* fix screw spacing in stl file for E-Paper HAT
