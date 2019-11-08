# esphome-config
Configuration files for esphome
# Serviceroom
This esphome configuration is an sonoff basic which is installed in one of the connection boxes in the service room.
## Configuration
* GPIO14  DHT22 temperature / humidity sensor
* GPIO3   SR501 PIR sensor

When the PIR sensor detects movement, the Green LED (Sonoff standard) + the relay (Sonoff standard) will be activated.
After 5 minutes of no movement detected, the relay will be switched off
Further esphome features installed: captive portal, restart switch, sensor for WiFi strength

