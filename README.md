# ESP8266 webserver controller
With an ESP8266 Arduino board and some Neopixels, this code can create a webserver that controls the neopixels light sequence.

There is no security or authentication on the webserver, and it is intented for people to play around with the lights.

## Requirements
### Hardware
- An ESP8266 board

- Neopixels. Read about [https://learn.adafruit.com/adafruit-neopixel-uberguide/best-practices](best practices here)

- 1, 300-500 Ohm resitor/per neopixel

- Soldering iron

- About 3 short wires for power, ground and data

### Software
- Arduino IDE, unless you use other cool stuff to program these boards.

- ESP8266 board drivers. `https://arduino.esp8266.com/stable/package_esp8266com_index.json`

- ESP8266 library. From Libary manager

- ESP-dash library. [https://github.com/ayushsharma82/ESP-DASH](https://github.com/ayushsharma82/ESP-DASH)
