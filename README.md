# Arduino Homekit Proof of Concept Project v2

This project was for me to build a proof of concept for controlling a LED natively through HomeKit using (https://github.com/Mixiaoxiao/Arduino-HomeKit-ESP8266|Arduino-Homekit-ESP8266). This will act as a catalyst for other projects for me, but can do so for you too. 

## What Did I Buy/Use Here?

- Bought: HiLetgo 3pcs ESP8266 on Amazon (https://www.amazon.com/gp/product/B081CSJV2V/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&th=1|Link)
- Used PlatformIO to make the whole experience easy as pie.
- Not much else, if you use the chipset I used just have PlatformIO open the NodeMcu 1.0 (ESP-12E Module) and it autotunes everything for you. I followed this article (https://www.losant.com/blog/getting-started-with-platformio-esp8266-nodemcu|Link)

## How Do I Get It Connected To My Wifi?

Open wifi_info.h and put in your SSID and wifi password.

## How Do I Get It To Do A Thing?

Open main.cpp and play around.

## How Do I Customize How It Looks On Homekit?

Open my_accesory.c and update the values.
