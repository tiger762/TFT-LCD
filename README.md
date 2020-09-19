###### TFT-LCD
TFT LCD 320x480 ILI9486 Raspberry Pi SPI stm32f407 cortex m4

###### If you have an stm32f4xxx in mind for a project, and want to add an LCD TFT screen intended for a Raspberry Pi, you're in the right place. The 3.5" LCD TFT for the RPI is sold in a lot of places. It uses a 2x13 female header that normally would plug into tjhe GPIO header of the RPI. There are only a handful of pins actually used. At a minimum, you'll connect:

- 5V
- GND
- RST
- RS
- MOSI
- SCLK
- CSN

###### I run the display in 16-bit color (RGB 5-6-5) mode. To compile the code, you'll need:

- gcc-arm-none-eabi

###### for your platform. Either use your package manager or download the source and compile it.
