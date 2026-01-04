# PicoBooster
5V booster for RasPi Pico.  Drives 5V peripherals but mainly aimed at WS2812 RGB LED strings. I really like the Pico from RasPi. Easy to program and I find the PIO feature very useful.

Features:
* Supports voltage translation for UART, I2C and SPI peripherals.
* Voltage translation individually selectable for UART, I2C and SPI.
* Voltage translation selectable between 3.3V and 5V.
* Supports WS2812 and WS2812B RGB LEDs.
* optional 100 uF capacitor to support longer WS2812 LED strings.
* optional external 5V input for large 5V loads.
* 4 pin JST XH (QWIIC) connector for I2C
* 3 pin JST XH connector for WS2812 strings
* Optional 2.54mm pin header connectors for UART, I2C, SPI and WS2812 LEDs.
* Run button support (allows firmware upload without unplugging USB).
* Supports castellation mounting of RasPi Pico for slim profile.
