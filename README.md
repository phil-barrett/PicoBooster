# PicoBooster
5V booster for RasPi Pico.  Drives 5V peripherals but mainly aimed at WS2812 RGB LED strings. I really like the Pico from RasPi. Easy to program and I find the PIO feature very useful.
![Booster Top](https://github.com/phil-barrett/PicoBooster/blob/main/Images/pico-booster-top.jpg)
Features:
* Supports WS2812 and WS2812B RGB LEDs.
* Supports voltage translation for UART, I2C and SPI peripherals.
  * Voltage translation individually selectable for UART, I2C and SPI.
  * Voltage translation selectable between 3.3V and 5V.
  * Bidirectional Voltage Translation on all pins.
* External power input for large 5V loads.
  * Optional 100 uF capacitor to support longer WS2812 LED strings.
  * Optional power from Pico/USB
* Multiple connectors 
  * 4 pin JST XH (QWIIC) connector for I2C
  * 3 pin JST XH connector for WS2812 strings
  * Optional 2.54mm pin header connectors for UART, I2C, SPI and WS2812 LEDs.
* Run button (allows firmware upload without unplugging USB).
* Supports castellation mounting of RasPi Pico for slim profile.

