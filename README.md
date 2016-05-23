Adafruit Python DHT Sensor Library
==================================

Python library to read the DHT series of humidity and temperature sensors on a Raspberry Pi, Beaglebone Black or a 96Boards compliant SOC.

Designed specifically to work with the Adafruit DHT series sensors ----> https://www.adafruit.com/products/385

Currently the library is only tested with Python 2.6/2.7.

For all platforms make sure your system is able to compile Python extensions.  On Raspbian or Beaglebone Black's Debian/Ubuntu image you can ensure your system is ready by executing:

````
sudo apt-get update
sudo apt-get install build-essential python-dev
````

Install the library by downloading with the download link on the right, unzipping the archive, and executing:

````
sudo python setup.py install
````

If you're running a 96Boards SOC (e.g. DragonBoard 410C) you'll need to install [libsoc][libsoc] and [96BoardsGPIO][96BoardsGPIO] before running the above. The implementation for 96Boards attempts to not be hardware specific but compliant to the 96Boards specification. It should work as long as `libsoc` supports the hardware.

See example of usage in the examples folder.

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Written by Tony DiCola for Adafruit Industries.

MIT license, all text above must be included in any redistribution

[libsoc]: https://github.com/jackmitch/libsoc
[96BoardsGPIO]: https://github.com/96boards/96BoardsGPIO