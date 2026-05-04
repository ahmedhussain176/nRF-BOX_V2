# nRFBox

                               DEMO || DEVELOPER

                            

Compact ESP32-based RF toolkit with an OLED icon UI, multi-radio nRF24L01 support, and on-device controls. Built for lab use and learning.

<img src="assets/nrfbox-prototype-bw.jpg" alt="nRFBox prototype on perfboard" width="600" />
<img src="assets/nrfbox-in-hand.jpg" alt="nRFBox handheld demo" width="600" />

## Highlights
- OLED icon menu with 12 modules and quick navigation
- BLE and Wi-Fi scanning views with detail pages
- Triple nRF24L01 radios with independent control
- NeoPixel status LED with toggle in Settings
- SD-based firmware update support

## Modules (menu)
- Scanner
- Analyzer
- WLAN Jammer
- Proto Kill
- BLE Jammer
- BLE Spoofer
- Sour Apple
- BLE Scan
- WiFi Scan
- Deauther
- About
- Setting

## Hardware
- ESP32 development board
- 3x nRF24L01+ modules (with antennas)
- 128x64 SSD1306 OLED (I2C)
- NeoPixel (single LED)
- 5x momentary buttons (Up, Down, Left, Right, Select)
- Optional SD card module (firmware updates)


## Controls
- Up/Down/Left/Right navigate the icon grid.
- Select opens a module; Select again returns to the main menu.
- Right button is also used for in-module actions where shown on screen.

## Build and flash
- Open [nRFBox.ino](nRFBox.ino) in Arduino IDE.
- Install the ESP32 board package.
- Install required libraries listed below.
- Select your ESP32 board and upload.

## Libraries
- U8g2
- Adafruit NeoPixel
- RF24
- ESP32 BLE (BLEDevice)
- WiFi (ESP32 core)
- SD, SPI, EEPROM, Update (ESP32 core)

## Firmware update
- Copy a file named /firmware.bin to the SD card.
- Use Settings -> Update Firmware from the device UI.

## Safety and legal
This project is for educational purposes only. It includes modules that can interfere with radio communications. Use only in controlled environments, on equipment you own, and where local laws allow it. You are responsible for compliance and safe operation.

## License
All rights reserved. This repository is shared for viewing only; no license is granted for reuse, modification, or redistribution.

## Acknowledgments
- Icons and UI are embedded in [icon.h](icon.h).
## Links
                            - Instagram: https://instagram.com/ahmed_hussain006
                            - GitHub: https://github.com/ahmedhussain176
