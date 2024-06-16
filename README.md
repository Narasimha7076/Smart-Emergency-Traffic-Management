# Smart Emergency Traffic Management

This project implements a smart traffic management system using an ESP8266 microcontroller, RFID technology, and Blynk platform. The system detects ambulances via RFID tags and controls traffic lights to give priority to the ambulance. The status is also displayed on an LCD screen and sent to the Blynk app for remote monitoring.

## Features

- **Ambulance Detection:** Uses RFID technology to detect the presence of an ambulance.
- **Traffic Light Control:** Automatically changes traffic lights to give priority to detected ambulances.
- **LCD Display:** Displays the current status of traffic lights and alerts drivers.
- **Remote Monitoring:** Sends real-time status updates to the Blynk app.
- **Smart Traffic Management:** Ensures smoother and faster passage for emergency vehicles.

## Hardware Requirements

- ESP8266 microcontroller
- RFID reader (MFRC522)
- RFID tags
- LCD display with I2C interface (LiquidCrystal I2C)
- LEDs for traffic lights (red and green)
- Resistors
- Breadboard and jumper wires

## Software Requirements

- Arduino IDE
- Blynk library
- ESP8266WiFi library
- MFRC522 library
- Wire library
- LiquidCrystal_I2C library
- SPI library


