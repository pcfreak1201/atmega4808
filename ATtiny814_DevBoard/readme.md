# ATtiny x04/x14/x24 Development Board
Development board for ATtiny x04/x14/x24 series with USB to serial converter and Arduino IDE support.

![ATtiny814_pic1.jpg](https://raw.githubusercontent.com/wagiminator/AVR-Development-Boards/master/ATtiny814_DevBoard/ATtiny814_DevBoard_pic1.jpg)

# Pinout
![ATtiny814_pinout.png](https://raw.githubusercontent.com/wagiminator/AVR-Development-Boards/master/ATtiny814_DevBoard/ATtiny814_DevBoard_pinout.png)

# Features of the tinyAVR

 Specifications |  ATtiny204|  ATtiny404  |  ATtiny804  |    ATtiny1604
:------------ | :------------- | :------------- | :------------- | :-------------
Flash (program memory)   | 2048 bytes | 4096 bytes | 8192 bytes | 16384 bytes
RAM  | 128 bytes | 256 bytes | 512 bytes | 1024 bytes
EEPROM | 64 bytes | 128 bytes | 128 bytes | 256 bytes
GPIO Pins | 12 (11 usable) | 12 (11 usable) | 12 (11 usable) | 12 (11 usable)
ADC Channels | 9 | 9 | 9 | 9
DAC | 0 | 0 | 0 | 0
PWM Channels | 6 | 6 | 6 | 6
Timer/Counter A | 1 | 1 | 1 | 1
Timer/Counter B| 1 | 1 | 1 | 1
Timer/Counter D | 0 | 0 | 0 | 0
Interfaces | UART, SPI, I2C | UART, SPI, I2C | UART, SPI, I2C | UART, SPI, I2C
Clock options | Internal 20/16/10/8/5/4/1 MHz | Internal 20/16/10/8/5/4/1 MHz | Internal 20/16/10/8/5/4/1 MHz | Internal 20/16/10/8/5/4/1 MHz

 Specifications |  ATtiny214|  ATtiny414  |  ATtiny814  |    ATtiny1614
:------------ | :------------- | :------------- | :------------- | :-------------
Flash (program memory)   | 2048 bytes | 4096 bytes | 8192 bytes | 16384 bytes
RAM  | 128 bytes | 256 bytes | 512 bytes | 2048 bytes
EEPROM | 64 bytes | 128 bytes | 128 bytes | 256 bytes
GPIO Pins | 12 (11 usable) | 12 (11 usable) | 12 (11 usable) | 12 (11 usable)
ADC Channels | 9 | 9 | 9 | 14
DAC | 1 | 1 | 1 | 3
PWM Channels | 6 | 6 | 6 | 6
Timer/Counter A | 1 | 1 | 1 | 1
Timer/Counter B | 1 | 1 | 1 | 2
Timer/Counter D | 1 | 1 | 1 | 1
Interfaces | UART, SPI, I2C | UART, SPI, I2C | UART, SPI, I2C | UART, SPI, I2C
Clock options | Internal 20/16/10/8/5/4/1 MHz | Internal 20/16/10/8/5/4/1 MHz | Internal 20/16/10/8/5/4/1 MHz | Internal 20/16/10/8/5/4/1 MHz

 Specifications | ATtiny424 | ATtiny824 | ATtiny1624 | ATtiny3224
:------------ | :------------- | :------------- | :------------- | :-------------
Flash (program memory)   | 4096 bytes | 8192 bytes | 16384 bytes | 32768 bytes
RAM  | 512 bytes | 1024 bytes | 2048 bytes | 3072 bytes
EEPROM | 128 bytes | 128 bytes | 256 bytes | 256 bytes
GPIO Pins | 12 (11 usable) | 12 (11 usable) | 12 (11 usable) | 12 (11 usable)
ADC Channels | 9 | 9 | 9 | 9
DAC | 0 | 0 | 0 | 0
PWM Channels | 6 | 6 | 6 | 6
Timer/Counter A | 1 | 1 | 1 | 1
Timer/Counter B | 2 | 2 | 2 | 2
Timer/Counter D | 0 | 0 | 0 | 0
Interfaces | 2xUART, SPI, I2C | 2xUART, SPI, I2C | 2xUART, SPI, I2C | 2xUART, SPI, I2C
Clock options | Internal 20/16/10/8/5/4/1 MHz | Internal 20/16/10/8/5/4/1 MHz | Internal 20/16/10/8/5/4/1 MHz | Internal 20/16/10/8/5/4/1 MHz

Note: The 0-series and 1-series parts have a 10-bit single-ended ADC with a sampling rate of up to 115 ksps, the 2-series parts have a 12-bit single-ended/differential ADC with a sampling rate of up to 375 ksps.

# Preparing Arduino IDE
- [Install megaTinyCore](https://github.com/SpenceKonde/megaTinyCore/blob/master/Installation.md)
- Open the Arduino IDE
- Go to "Tools" -> "Board" -> "megaTinyCore" and select your chip
- Go to "Tools" and set the desired board options
- Go to "Tools" -> "Programmer" and select "jtag2updi(megaTinyCore)"
- Connect the UPDI programmer to the UPDI header on the development board. You can find such programmers in my [projects](https://github.com/wagiminator/AVR-Programmer) or you can use an [Arduino Uno as a UPDI programmer](https://github.com/SpenceKonde/megaTinyCore/blob/master/MakeUPDIProgrammer.md).
- Go to "Tools" -> "Burn Bootloader"
- Now you can upload your sketch

# References, Links and Notes
- Getting started with the new ATtiny chips: http://www.technoblogy.com/show?2OCH
- The ATtiny 2-Series: http://www.technoblogy.com/show?3UKF
- megaTinyCore: https://github.com/SpenceKonde/megaTinyCore
- UPDI Programmer: https://github.com/wagiminator/AVR-Programmer
- AVR Development Boards: https://github.com/wagiminator/AVR-Development-Boards

![ATtiny814_pic2.jpg](https://raw.githubusercontent.com/wagiminator/AVR-Development-Boards/master/ATtiny814_DevBoard/ATtiny814_DevBoard_pic2.jpg)

# License

![license.png](https://i.creativecommons.org/l/by-sa/3.0/88x31.png)

This work is licensed under Creative Commons Attribution-ShareAlike 3.0 Unported License. 
(http://creativecommons.org/licenses/by-sa/3.0/)
