# Air-Quality-Monitoring-System

This repository contains the full source code and documentation for the Air Quality Monitoring System developed as part of a final-year project. The system is designed to monitor multiple environmental pollutants in real-time, including CO, NO₂, NH₃, CO₂, PM2.5, PM10, and combustible gases.

## Features

- Real-time gas and particulate matter detection
- OLED local display for immediate data visualization
- Wi-Fi-based remote data transmission (HTTP/JSON)
- Web dashboard for live monitoring and WHO threshold comparison
- Local data logging to SD card
- Buzzer-based threshold alerts
- Low-cost hardware design based on ESP32 and Arduino
- Fully open-source and customizable

## Hardware Components

- ESP32 Development Board
- Arduino Uno R3 
- MQ-2 Gas Sensor (combustible gases)
- MICS6814 Gas Sensor (CO, NO₂, NH₃)
- MH-Z19B CO₂ Sensor
- SDS011 PM2.5/PM10 Sensor
- OLED 0.96'' Display
- SD Card Module
- Buzzer Module
- Custom Laser-Cut Acrylic Enclosure


## Setup Instructions

1. **Hardware Assembly**  
Connect sensors according to the provided wiring diagrams. Assemble the custom enclosure using laser-cut acrylic panels.

2. **Software Setup**  
Flash Arduino and ESP32 with the respective source codes. Install required libraries (ArduinoJson, WiFi, Adafruit_SSD1306, etc.). Set up the backend server using Node.js.

3. **Web Interface**  
Deploy the frontend dashboard to a hosting service or local server.

4. **Testing**  
Power on the system and verify live data on the OLED and web dashboard. Validate SD card logging and buzzer alerts when pollutant thresholds are exceeded.


## Future Improvements

- Integration of PCB
- Environmental compensation algorithms for MOS sensor outputs
- Tested multiple times in different environments
- Use a more stable power supply


## Contact

For any inquiries or collaboration opportunities, please contact:  
**Chaoshuo Han**  
**sgchan7@liverpool.ac.uk**
