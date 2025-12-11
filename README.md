# TCS34725_RGB-Color-Sensor__RasberryPi

The [TCS34725 RGB sensor](https://learn.adafruit.com/adafruit-color-sensors/overview) provides a digital return of red, green, blue (RGB), and clear light sensing values. An RGB Color sensor helps you accurately detect an object’s colour in your interactive projects.

----
**TCS34725 on-board white LED**

Used to provide constant illumination. 

The LED pin can be pulled low to turn off the LED. This can be done by:

  1. Wiring directly to ground to turn it off completely.
     
  2. Wiring to a spare digital pin and control it with digitalWrite().

----
# TUTORIAL SET-UP for Raspberry Pi
----
### HARDWARE

- Raspberry Pi
- TCS34725 sensor
----
### WIRING
Raspberry Pi GPIO [diagram here](https://github.com/kingston-hackSpace/RaspberryPi/blob/main/GPIO-diagram.png)

RGB Sensor | RPi GPIO
-|-
GND | GND
VIN | 3.3V
SDA | SDA / GPIO2 / Pin3
SCL| SCL / GPIO3 / Pin5

----
### Python
----

Our programming language for this tutorial will be *Python*, which is the standard programming language included with a Raspberry Pi.

Learn more about Python [here](https://www.python.org/)

----
### PROGRAMMING INSTRUCTIONS

- Open the Raspberry Pi's Terminal (black top left icon).

- Your terminal should pop-up, looking similar to [this]

- From now on we will be typing instructions on the terminal.


# Using the terminal

- Updating device and installing all necessary protocols:

  ```
  sudo apt update && sudo apt upgrade -y
  sudo apt install -y python3-pip i2c-tools
  ```

- Install the tcs34725 sensor library:

  `sudo pip3 install adafruit-circuitpython-tcs34725`





----
### MORE TUTORIALS

- [Interfacing a TCS34725 RGB Color Sensor With Arduino – A Complete Guide](https://www.makerguides.com/tcs34725-rgb-color-sensor-with-arduino/)

- [LED lighting based on colour readings](https://learn.adafruit.com/adafruit-color-sensors/arduino-code)
