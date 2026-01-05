# PicoBooster
5V booster for RasPi Pico.  Drives 5V peripherals but mainly aimed at WS2812 RGB LED strings. I really like the Pico from RasPi. Easy to program and I find the PIO feature very useful.
![Booster Top](https://github.com/phil-barrett/PicoBooster/blob/main/Images/pico-booster-top.jpg)
# Features:
* Supports WS2812 and WS2812B RGB LEDs.
* Supports voltage translation for UART, I2C and SPI peripherals.
  * Voltage translation individually selectable for UART, I2C and SPI.
  * Voltage translation selectable between 3.3V and 5V.
  * Bidirectional Voltage Translation on all pins.
* Flexible Power
  * External power input for large 5V loads.
  * Optional 100 uF capacitor to support longer WS2812 LED strings.
  * Optional power from Pico/USB
* Multiple connectors 
  * 4 pin JST XH (QWIIC) connector for I2C
  * 3 pin JST XH connector for WS2812 strings
  * Optional 2.54mm pin header connectors for UART, I2C, SPI and WS2812 LEDs.
* Run button (allows firmware upload without unplugging USB).
* Supports castellation mounting of RasPi Pico for slim profile.
# Questions/Musings
Please feel free to comment on these in Discussions
* Booster was designed with a very specific purpose in mind (drive 5V WS LEDs from 3.3V microcontroller). However, feature creep started immediately (hence UART, I2C, SPI, QWIIC).  Is there anything obvious I am missing?
* For external power, I the provided screw terminal good enough or is a standard barrel jack a better idea?
* I used a JST XH (2.50mm) connector. Many NEOPixel devices use smaller (JST SH 1.00 mm). Given that there does not seem to be standardization of the pin assignments, a new cable is likely to be needed.  The 2.50 mm ones are easier to work with.
* Should I use horizontal JST connectors rather than vertical (as shown in the images).
* Anything I need to do to support Python?
