# ESP32-C6 WeAct 2.9-inch Epaper Module Display-Info

This is the accompanying repository for my article "Getting Started with a 2.9-inch Epaper display connected to an ESP32-C6 Supermini device" available here: https://medium.com/@androidcrypto/getting-started-with-a-2-9-inch-epaper-display-connected-to-an-esp32-c6-supermini-device-ce3a4bb6d2a6

![Image 1](./images/esp32_c6_epaper_04_600w.png)

The display comes in 2 variants, this is the "Black & White" version:

![Image 2](./images/esp32_c6_epaper_02_600w.png)

The display comes in 2 variants, this is the "Red, Black & White" version:

![Image 3](./images/esp32_c6_epaper_01_600w.png)

## Required Libraries
````plaintext
GxEPD2 by "ZinggJM" version 1.6.4 (https://github.com/ZinggJM/GxEPD2)
Adafruit-GFX-Library by "Adafruit" version 1.12.1 (https://github.com/adafruit/Adafruit-GFX-Library)
U8G2_FOR_ADAFRUIT_GFX by "olikraus" latest version (https://github.com/olikraus/u8g2/)
````

## Runtime Environment
````plaintext
Arduino 2.3.6 (Windows)
esp32 boards version 3.2.0
For compiling and uploading, I'm using the "ESP32-C6 Dev Module" board
````

## Wiring
````plaintext
Nr name  color   ESP32-C6 pin
1  BUSY  violet  16 (labled as 'TX')
2  RES   orange  21
3  D/C   white   19
4  CS    blue    20
5  SCL   green   17 (labled as 'RX')
6  SDA   yellow  14 ('SDA' terminal is known as 'MOSI')
7  GND   black   GND
8  VCC   red     VCC is 3.3 volt, not 5 volt !
````
Back side of the display:

![Image 2](./images/esp32_c6_epaper_03_600w.png)
