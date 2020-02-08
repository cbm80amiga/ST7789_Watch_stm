# ST7789_Watch_stm
Analog Watch/Clock with STM32 RTC and ST7789 IPS

# YouTube videos
https://youtu.be/35Z0enhEYqM
https://youtu.be/jFGDFuLhdMc 

# Features
- STM32 internal RTC with backup battery was used
- a few color clock faces taken from the internet
- one clock face in 240x240 pixel resolution compressed to 4-bits takes only 29K of memory so even 2 could fit in STM32 memory
- watch hands are are vector based
- no floating-point arithmetic and slow trigonometric functions were used

## Connections:

|LCD pin|LCD pin name|Arduino|
|--|--|--|
 |#01| GND| GND|
 |#02| VCC |3.3V|
 |#03| SCL |PA5|
 |#04| SDA|PA7|
 |#05| RES|PA0 or any digital|
 |#06| DC|PA1 or any digital|
 |#07| BLK | NC|


If you find it useful and you want to buy me a coffee or a beer:

https://www.paypal.me/cbm80amiga
