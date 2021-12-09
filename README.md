SparkFun MicroMod GNSS Carrier Board (ZED-F9P)
========================================

[![SparkFun MicroMod GNSS Carrier Board (ZED-F9P)](https://cdn.sparkfun.com/assets/parts/1/6/8/3/0/17722-SparkFun_MicroMod_GNSS_Carrier_Board__ZED-F9P_-01.jpg)](https://www.sparkfun.com/products/17722)

[*SparkFun MicroMod GNSS Carrier Board (ZED-F9P) (GPS-17722)*](https://www.sparkfun.com/products/17722)

With GNSS you are able to know where you are, where you're going, and how to get there anywhere on Earth within 30 seconds. This means the higher the accuracy the better! GNSS Real Time Kinematics (RTK) has mastered dialing in the accuracy of their GNSS modules to just millimeters, and that's why we had to put it on this board! With the flexibility of the MicroMod's M.2 connector, you can easily test and swap out different MicroMod processor boards for your application. Simply match up the key on your board's beveled edge connector to the key on the M.2 connector and secure the boards with a screw.

The SparkFun MicroMod GNSS Carrier Board raises the bar for high-precision GPS and is in a line of powerful RTK boards featuring the ZED-F9P module from u-blox. The ZED-F9P is a top-of-the-line module for high accuracy GNSS and GPS location solutions including RTK that is capable of 10mm, three-dimensional accuracy. With this board, you will be able to know where your (or any object's) X, Y, and Z location is within roughly the width of your fingernail! The ZED-F9P is unique in that it is capable of both rover and base station operations. Utilizing the M.2 and Qwiic connectors, no soldering is required to connect it to the rest of your system. However, we still broke out 0.1"-spaced pins in case you prefer to use a breadboard to attach additional peripherals.

The board includes two USB-C connectors for power and programming. Two buttons for reset and boot are also populated on the board. A 2A resettable fuse and 3.3V/1A voltage regulator are built-in to the board for power. We've even added a convenient jumper for advanced users looking to bypass the fuse and another to measure the current consumption for low power testing. Five status LEDs are available for power, 3.3V, PPS, RTK, and geofencing. These can also be disabled via the jumper pads. One SMA connector is included for a secure connection to an antenna. For those that need a secure connection to the PPS pin, the SMA connector footprint is included in the design so that you can manually solder it to the board for your application. Finally, one Qwiic connector is populated on the board to easily add Qwiic enabled I<sup>2</sup>C devices to your projects!


We've even included a rechargeable backup battery to keep the latest module configuration and satellite data available for up to two weeks. This battery helps 'warm-start' the module, decreasing the time-to-first-fix dramatically. This module features a survey-in mode allowing the module to become a base station and produce RTCM 3.x correction data.

The number of configuration options of the ZED-F9P is incredible! Geofencing, variable I<sup>2</sup>C address, variable update rates, even the high precision RTK solution can be increased to 20Hz. The MicroMod GNSS carrier board even has five communications ports, four of which are all active simultaneously: USB-C (which enumerates as a COM port), UART1 (with 3.3V TTL), UART2 for RTCM reception (with 3.3V TTL), I<sup>2</sup>C (via the one Qwiic connector or broken out pins), and SPI.

We've also written an extensive [Arduino library for u-blox modules](https://github.com/sparkfun/SparkFun_u-blox_GNSS_Arduino_Library) to make reading and controlling the MicroMod GNSS carrier board over the MicroMod's I<sup>2</sup>C bus is easy. Leave NMEA behind! Start using a much lighter weight binary interface and give your microcontroller (and its one serial port) a break. The SparkFun Arduino library shows how to read latitude, longitude, even heading and speed over I<sup>2</sup>C without the need for constant serial polling.

Repository Contents
-------------------

* **/Hardware** - Eagle design files (.brd, .sch)
* **/Production** - Production panel files (.brd)

Documentation
--------------
* **[Library](https://github.com/sparkfun/SparkFun_u-blox_GNSS_Arduino_Library)** - Arduino library for the u-blox modules (e.g. ZED-F9P)
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/2187)** - Basic hookup guide for the ZED-F9P Carrier Board

Product Versions
----------------
* [GPS-17722](https://www.sparkfun.com/products/17722) 

Version History
---------------
* v1.0 - initial release


License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.

_<COLLABORATION CREDIT>_
