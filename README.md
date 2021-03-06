Freetronics FreeNFET Addressable N-MOSFET Module
================================================
Copyright 2016 Freetronics Pty Ltd  
Freetronics site:  www.freetronics.com  
Freetronics email: info@freetronics.com  

This is a FET with a brain! Includes an NTD5867NL N-channel MOSFET and
a WS2811 addressable LED driver. That means you can connect the module
and address it just as if it was a NeoPixel or other WS28xx RGB LED, 
except that instead of controlling an LED, you're controlling a high-power
MOSFET.

This smart module can be daisy-chained, so you can connect a number of
these together in a string and drive each of them individually from your
microcontroller.

Compatible with various Arduino libraries for the WS2811, including
the FastLED library and the NeoPixel library. Simply control the "red"
channel to control the FET.

Features:

 * Switch up to 60V / 18A DC.
 * Requires just 1 data connection.
 * PWM control of the FET.
 * Input and output headers on opposite sides of the board for easy
   daisy-chaining.

More information is available at:

  http://www.freetronics.com.au/freenfet


INSTALLATION
------------
The design is saved as an EAGLE project. EAGLE PCB design software is
available from www.cadsoftusa.com free for non-commercial use. To use
this project download it and place the directory containing these files
into the "eagle" directory on your computer.


DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the
license referenced below.


LICENSE
-------
Licensed under the TAPR Open Hardware License (www.tapr.org/OHL).
The "license" folder within this repository also contains a copy of
this license in plain text format.
