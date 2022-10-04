# Iconic_Eye
## Just import the code into your Arduino IDE and give the correct credentials of the telegram bot id and token and thats it......Before that install the necessary libraries for that
Installing ESP32 Add-on in Arduino IDE
To install the ESP32 board in your Arduino IDE, follow these next instructions:
1. In your Arduino IDE, go to File> Preferences
2. Enter the following into the “Additional Board Manager URLs” field:
    https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json,http://arduino.esp8266.com/stable/package_esp8266com_index.json
#Note: if you already have the ESP8266 boards URL, you can separate the URLs with a comma as follows:
3. Open the Boards Manager. Go to Tools > Board > Boards Manager…
4. Search for ESP32 and press install button for the "ESP32 by Espressif Systems":
5. That’s it. It should be installed after a few seconds.
6. Now select your Board in Tools > Board menu > YOUR MODEL CAMERA.
