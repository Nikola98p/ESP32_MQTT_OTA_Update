# ESP32 Web Server with OTA Firmware Update

This project implements an ESP32-based web server that facilitates Over-The-Air (OTA) firmware updates. It includes the necessary libraries for WiFi connectivity, web server functionality, MDNS resolution, and firmware updating. 

## Setup
1. Include your WiFi credentials in `creds.h`.
2. Customize the UI styling in `style.h`.
3. Upload the sketch to your ESP32 device.
4. Access the web interface to upload firmware updates.

## Usage
- Connect to the ESP32 WiFi network.
- Navigate to `http://esp32.local` in your web browser.
- Log in with the provided credentials.
- Choose a firmware file for updating.
- Monitor the update progress.
- Upon completion, the device will automatically reboot.

## Libraries Used
- WiFi.h
- WiFiClient.h
- WebServer.h
- ESPmDNS.h
- Update.h

For detailed setup instructions and usage, refer to the comments within the code.
