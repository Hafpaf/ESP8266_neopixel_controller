# ESP8266 webserver controller
With an ESP8266 Arduino board and some Neopixels, this code can create a webserver that controls the neopixels light sequence.

There is no security or authentication on the webserver, and it is intented for people to play around with the lights.

## Requirements
### Hardware
- An ESP8266 board

- Neopixels. Read about [best practices here](https://learn.adafruit.com/adafruit-neopixel-uberguide/best-practices)

- 1, 300-500 Ohm between data and first pixel

- 1 ohm resistors between each Neopixel

- Soldering iron

- About 3 short wires for power, ground and data

- Something to solder on

### Software
- Arduino IDE, unless you use other cool stuff to program these boards.

- ESP8266 board drivers. Input the following into 'File -> Preferences -> Additional Boards Manager URLs':`https://arduino.esp8266.com/stable/package_esp8266com_index.json`

- ESP8266 library: Found in libary manager

- Adafruit neopixel library: Found in library manager

- ESPAsyncTCP library: [https://github.com/me-no-dev/ESPAsyncTCP](https://github.com/me-no-dev/ESPAsyncTCP) 

- ESPAsyncWebServer: [https://github.com/me-no-dev/ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer)

- ESP-dash library: [https://github.com/ayushsharma82/ESP-DASH](https://github.com/ayushsharma82/ESP-DASH)

## Notes
There is a few things to note about ESP8266_neopixel_controller:

- Set the SSID and password to connect to the wifi

- Set `LED_PIN` and `LED_COUNT` correctly.

- The boards IP address will be printed out with Serial.print and can be found by opening the serial monitor.

## Ressources
- ESP8266_neopixel_controller is based of [ESP-DASH ESP8266_blink.ino](https://github.com/ayushsharma82/ESP-DASH/blob/master/examples/ESP8266_blink/ESP8266_blink.ino) and [Neopixel strandtest.ino](https://github.com/adafruit/Adafruit_NeoPixel/blob/master/examples/strandtest/strandtest.ino)
