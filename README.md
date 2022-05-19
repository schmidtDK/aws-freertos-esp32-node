# aws-freertos-esp32-node
Firmware for IoT monitoring based on ESP32 and AWS FreeRTOS

## Brief description
PoC Firmware for IoT node based on ESP32 connecting to AWS IoT core. Support for multiple pollution sensors (EC, PM, T, RH). Configuration via device shadow. MQTT based telemetry and control.

## Features
1. Main
2. Configuration
3. Connectivity
4. Sensors
5. Telemetry
6. Control

### Main
xyz
databuffer
time keeping RTC

### Configuration
See xxxxxx

### Connectivity
Support for both WiFi and cellular based connectivity to AWS IoT Core. 

#### Wifi
Based on ESP32 WiFi modem

#### Cellular
Based on Ublox SARA-R510 cellular modem (3G / 4G / 5G)

### Sensors
Support for SPS30, SCD30, SHTx, Airlabs EC analog frontend (ALEC) up to 4 cells.

### Telemetry
Generate JSON payload based on sensor readings

### Control
xxxxxx
