# Code for lora sender and receiver test
seperate arduino platformio scetches for an esp sender node and receiver node. Code mostly from following tutorial:
https://randomnerdtutorials.com/esp32-lora-rfm95-transceiver-arduino-ide/

Used a LilyGO TTGO T-Beam ESP32 based lora board:
https://www.tinytronics.nl/shop/en/development-boards/microcontroller-boards/with-gps/lilygo-ttgo-t-beam-lora-868mhz-neo-6m-gps-esp32

In combination with a HopeRF RFM95W LoRa Module connected to a ESP32:
https://www.tinytronics.nl/shop/en/communication-and-signals/wireless/lora/modules/hoperf-rfm95w-lora-module-868mhz

# Setup
used the t-beam as a receiver. just the t-beam out of the box with the factory SPI and Lora pins.

Allso used the esp32 with the LoRa module as a sender, as with the factory SPI and LoRa pins.
