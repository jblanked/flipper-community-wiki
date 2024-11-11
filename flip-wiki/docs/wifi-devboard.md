# Official Wi-Fi Development Board.
The official WiFi development board sold by Flipper Devices is at it's core an ESP32-S2, which can be technically be flashed with any firmware that supports the ESP32. While the board does support Wi-Fi, the S2 model **does not support Bluetooth.**

## Official Purpose Of The Wi-Fi Development Board
The official Wi-Fi development board sold by Flipper Devices is geared primarily for debugging firmware and application for the Flipper Zero. Due to this, it arrives pre-flashed with the [BlackMagic](https://github.com/flipperdevices/blackmagic-esp32-s2) firmware to enable both wired and wireless debugging. 

Documentation for how to begin debugging with the board can be found in the [official flipper zero documentation](https://developer.flipper.net/flipperzero/doxygen/dev_board_get_started.html). 

## Community Uses For The Board
If one does not desire to do development with the board or wants to try a different use for the board, it is possible to flash the Wi-Fi board with alternate firmware to try new functions. 

The following is a partial list of a few popular community firmware that one may use for the board that also have companion apps for the Flipper Zero:

- [Marauder](https://github.com/justcallmekoko/ESP32Marauder/wiki/flipper-zero), an offensive security testing platform for ESP32 based devices, featuring both Wi-Fi tools and Bluetooth tools for hardware supporting bluetooth. 
- [FlipperHTTP](https://github.com/jblanked/FlipperHTTP), a multi-purpose firmware for pulling in info from the web for easy viewing on your flipper, as well as making social posts on the FlipSocial platform.
- [GhostESP](https://github.com/Spooks4576/Ghost_ESP), a firmware that provides tools to perform comprehensive WiFi and Bluetooth Low Energy (BLE) analysis, execute targeted wireless tests, and explore dynamic wireless environments.


## Useful Links
- [FZEE flasher](https://fzeeflasher.com), an easy web based ESP flasher for installing popular firmware with only a few clicks. 
- [EspWebTool](https://esp.huhn.me), a more manual and general purpose web flasher tool for all ESP32 devices, requires having pre-built firmware binaries. 