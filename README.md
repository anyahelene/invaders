# invaders
##### A hand-held retro console based on the ATmega328P chip

## Features
* [ATmega328P](https://www.microchip.com/wwwproducts/en/ATMEGA328P) as the CPU, with
   * 16 MHz clock
   * 32 KiB flash memory for programs
   * 2 KiB static ram
   * 1 KiB EEPROM
* Choice of one of three OLED displays:
   * 2.42" monochrome 128x64 OLED with SPI interface, e.g., [this one from DIYMORE](https://www.diymore.cc/collections/display-module/products/2-42-inch-12864-oled-display-module-iic-i2c-spi-serial-for-arduino-c51-stm32-green-white-blue-yellow)
   * 1.5" color 128x128 OLED with SPI interface, e.g., [this one from Waveshare](https://www.waveshare.com/1.5inch-RGB-OLED-Module.htm)
   * 1.3" monochrome 128x64 OLED with I2C interface, found as infinite clones such as [this one from Luxorparts](https://www.kjell.com/no/produkter/elektro-og-verktoy/elektronikk/optokomponenter/led-lcd-skjermer/luxorparts-grafisk-oled-skjerm-128-x-64-piksler-1-3--p87946)
   * The board has pin headers and mounting holes for these three displays, but other display sizes might fit, and different pinouts might be accommodated by wires
   * The above displays are available from Ebay ($2.50 for a small display, up to ~$18 for large/color), and similar displays can be found at [Adafruit](https://adafruit.com/), [Sparkfun](https://sparkfun.com/) or your local electronics store
* Four directional buttons on the left-hand side
* Thumbstick *or* two buttons on the right-hand side
* Two trigger buttons on the top edge
* Reset button on the bottom side
* Space for 2xAAA batteries + also a JST-PH battery connector (as seen on the micro:bit)
* Micro USB power connector
* 6 pin AVR ICSP header for programming
* Space for a tiny speaker/buzzer
* Power led + two controllable leds

## Circuit board
* [KiCad](http://www.kicad-pcb.org/) files for the board can be found in the [pcb/](pcb/) subdirectory.
* Alternatively, the board can be manufactured directly from the Gerber files in [pcb/fab/](pcb/fab/).
