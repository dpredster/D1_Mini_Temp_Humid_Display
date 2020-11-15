# D1_Mini_Temp_Humid_Display
Demo of integration of Wemos D1 Mini(ESP8266), BME280 Temperature Humidity Pressure Sensor and 0.96 inch OLED Display.

The libraries required for this project are Adafruit_SSD1306 library and Adafruit_GFX library for the OLED display and, Adafruit_Sensor library and Adafruit_BME280 library for the BME280.
 
There are two ino files with the same functionalty. The only difference is the EE_D1_TempHumidDisplay_w_Icon.ino shows the use of icons in the sketch.

## Project Pinout
##### WARNING!: THIS PINOUT IS FOR THE 5V VERSION OF BME280. IF YOU HAVE THE 3.3V VERSION CONNECT YOUR POWER TO THE 3.3V PIN ON THE D1 MINI (The display would work with 3.3V or 5V).

![Image of Pinout](https://raw.githubusercontent.com/dpredster/D1_Mini_Temp_Humid_Display/main/project_pinout.png)
