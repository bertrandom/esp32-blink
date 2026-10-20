# esp32-blink

I have a bunch of these generic ESP32 boards that I purchased from [Amazon](https://www.amazon.com/dp/B08DQQ8CBP) about 5 years ago.

This repo is a starting PlatformIO project for building on them, it has the correct board selected and has a generic blink sketch.

The back of the board has `ESP32 DEVKITV1` written on it.

The headers are unsoldered. Have fun soldering 30 pins per board!

I have since moved on to these alternatives which are smaller:

| Board | Link | Price |
|---|---|---|
| M5Stack NanoC6 Dev Kit | https://shop.m5stack.com/products/m5stack-nanoc6-dev-kit | $5.95 |
| Seeed Studio XIAO ESP32-S3 | https://www.seeedstudio.com/XIAO-ESP32S3-p-5627.html | $7.50 |
| Seeed Studio XIAO ESP32-C6 | https://www.seeedstudio.com/Seeed-Studio-XIAO-ESP32C6-p-5884.html | $5.20 |

but sometimes you still need a lot of pins. And I have a lot of these in a drawer.

## Pinout

<img width="966" height="574" alt="ESP32-DOIT-DEVKIT-V1-Board-Pinout-30-GPIOs-Copy" src="https://github.com/user-attachments/assets/1fa2480c-a23a-4406-a918-731403d1699c" />

<img width="498" height="316" alt="51bDr36Gk6L _AC_" src="https://github.com/user-attachments/assets/87aebe89-960d-4c81-a649-f33e2902bab3" />

## Board

<img width="1024" height="683" alt="esp32-devkit-side-by-side" src="https://github.com/user-attachments/assets/beb4dc57-c1b6-4ca9-ade4-9988d7992a9b" />

## Notes

I have successfully flashed one of these with the ESPHome Bluetooth Proxy: https://esphome.io/projects/?type=bluetooth