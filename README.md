# ESP32 GPS Tracker with Email Integration
This project demonstrates how to create a GPS tracker using the ESP32/ESP8266 module and send the current location via email. When the user presses a button, the program retrieves the current location from the GPS module and creates a Google Maps URL for it. It then connects to a Wi-Fi network and sends the location to a specified recipient via email.

# Features
- Retrieves GPS location and creates a Google Maps URL
- Connects to a Wi-Fi network
- Sends location via email using the SMTP protocol

# Hardware Requirements
- ESP32 WROOM module
- GPS NEO-6M
- Button
- wires and breadboard

# Installation
1. Clone or download the repository.
2. Open the Arduino IDE and install the required libraries (WiFi, ESP_Mail_Client, TinyGPSPlus).
3. Connect the hardware components as described in the wiring diagram.
4. Configure the Wi-Fi and email settings in the code.
5. Upload the code to the ESP8266 module.
6. Press the button to send the current location via email.

# Connection 
| ESP32 | GPS   |
|-------|-------|
| 3V3   | VCC   |
| GND   | GND   |
| RX    | TX    |
| TX    | RX    |

# LED status on the GPS module
⚫ No blinking – it is searching for satellites.
⚫ Blink every 1s – Position Fix is found (the module can see enough satellites).


