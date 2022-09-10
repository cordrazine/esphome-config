# esphome-config
Configuration files for esphome

# ESP32_Service (Serviceroom)
This esphome configuration is a ESP32 which is installed in one of the connection boxes in the service room.
It reads out the temperature / humity using a DHT22 and has a SR501 PIR sensor.

The light of the service room is controlled by a shally 1
The dehumifier is controlled by a Shelly Plug S

When movement is detected, the motion will be send to Home-Assistant where alll the autmation is handled.

## Configuration
* GPIO4  DHT22 temperature / humidity sensor
* GPIO2   SR501 PIR sensor


Further esphome features installed: captive portal, OTA, restart switch, version, connect status WiFi strength.

# Bed
Description follows

# Common
A collection of common code snippet used in the main yaml.
Here you can find uptime switches, wifisignalstrength sensors etc.
They have been used in several projects so validated.

Connection status   - Binary Sensor reporting if device is connected
Version text info   - Text Sensor reporting the version of ESPHOME used during compiling
Wifi Info           - Text Sensor reporting to which Wifi the node is connected
Restart             - Restart Switch for rebooting the node

