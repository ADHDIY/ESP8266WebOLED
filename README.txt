This is the pin out I used for the SPI OLED to the ESP8266
You can change it, but you will need to edit the code as well 
for more information you can go to this website I used when researching
https://www.electronicshub.org/nodemcu-esp8266-oled-display/

Make sure that you install the ESP8266 and U8G2 Libraries 
Also replace STASSID and STAPSK with your WiFi's SSID and Password

Lable || Pin 
GND   >> GND
VCC   >> 3V3
CLK   >> D5 
MOSI  >> D7
RES   >> D3
DC    >> D1
CS    >> D8