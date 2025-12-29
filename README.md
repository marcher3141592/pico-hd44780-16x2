# Raspberry Pi Pico 16x2 HD44780 LCD library
A simple library to interface 16x2 HD44780 based LCDs with the Raspberry Pi Pico, using the C SDK.

Function usage is explained in detail in the header file. A simple example is included.
## Compatibility
This library has been tested only on the Raspberry Pi Pico W (RP2040), but since it only uses basic GPIO functions it should have no problems working on other boards.
## Known issues
+ The library has been been tested only with a 16x2 LCD. In theory it should work on any two-column LCD.
+ If the microcontroller is soft-reset the library is unable to re-init the display. It's necessary to hard-reset the display and the microcontroller.
## Contributing
This library is still far from complete, so any feedback or help with coding is appreciated ❤️
