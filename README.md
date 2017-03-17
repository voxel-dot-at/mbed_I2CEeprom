# mbed_I2CEeprom

Adapted libraby from Robin Hourahane's work https://developer.mbed.org/users/rhourahane/code/I2CEeprom/

This class provides a simple read write interface for I2C EEPROMs like Microchip's 24LC range and AMTELS AT24C and LU218 range. The class ensure that writes respect the page size of the chip to ensure larger blocks can be written in one call. The class uses the supplied buffer to directly write to the chip so no extra RAM is used.

Library descriptors have been added for Platformio IDE
