SparkFun Particle Photon Library
===============================================

This is a library for the SparkFun BME280 Humidity, Barometric Pressure + Temp sensor

Particle Photon, Core & Electorn Library based on Sparkfun Arduino Library for BME280 sensors adapted by Markus Haack

Designed specifically to work with the [*SparkFun BME280 (SEN-13676)*](https://www.sparkfun.com/products/13676)

Works with the following BME280-Breakouts as well:
 * http://www.watterott.com/en/BME280-Breakout-humidity-pressure-temperature-sensor
 * http://www.adafruit.com/products/2652

This library allows the user to:

* Read pressure in Pa
* Read temperature in C
* Read humidity in %RH

It also provides the following mathematical functions based from the above.

* Read temperature in F
* Read altitude in meters
* Read altitude in feet

Some examples include a circular buffer class for averaging.

Repository Contents
-------------------

* **/examples** - Example sketches for the library (.ino). Run these from the Arduino IDE. 
* **/src** - Source files for the library (.cpp, .h).
* **library.properties** - General library properties for the Arduino package manager. 

Documentation
--------------

* **[Installing an Arduino Library Guide](https://learn.sparkfun.com/tutorials/installing-an-arduino-library)** - Basic information on how to install an Arduino library.
* **[Product Repository](https://github.com/sparkfun/BME280-Breakout-Board)** - Main repository (including hardware files) for the SparkFun BME280 Breakout.
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/bme280-breakout-hookup-guide)** - Basic hookup guide for the SparkFun BME280 Breakout.

Version History
---------------
* [V_1.0.0](https://github.com/mhaack/SparkFun_BME280/releases/tag/V_1.0.0) - October 2015 Initial Release
* [V_1.1.1](https://github.com/mhaack/SparkFun_BME280/releases/tag/V_1.1.1) - January 2017 migrated to V2 library, pulled minor changes

License Information
-------------------

Original Arduino library: https://github.com/sparkfun/SparkFun_BME280_Arduino_Library

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact techsupport@sparkfun.com.

Distributed as-is; no warranty is given.
