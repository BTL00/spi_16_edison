# spi_16_edison
Modified SPI library for Intel Edison Arduino Breakout Kit that allows SPI.transfer16() function.

Intel hasn't updated SPI library for a long time. It is not compatible with lots of other stuff. I try to add all functions that are included in AVR version.

Installation for Arduino 1.6.6:
> go to AppData\Roaming\Arduino15\packages\Intel\hardware\i686\1.6.2+1.0\libraries\SPI\src
> create backup of files in folder
> overwrite SPI.h and SPI.cpp files

Added functions:
>  byte transfer(byte _data); AVR compatible transfer function;
>  int16_t transfer16(int16_t _data); Allows you to send 2 byte variables at once. Useful to work with displays;


  
