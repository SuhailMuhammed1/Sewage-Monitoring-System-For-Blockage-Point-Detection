# Sewage Monitoring System For Blockage Point Detection

This Arduino sketch implements a Sewage Monitoring System for Blockage Point Detection. The system utilizes a NodeMCU board, various sensors, and the Arduino IoT Cloud to monitor distance, water level, and GPS coordinates. It also includes automated alerts and visualization of data on the IoT Cloud dashboard.

## Step 1: Installation

### Install Arduino IDE

1. Open `File` -> `Preferences` -> `Settings`.
2. Type `https://arduino.esp8266.com/stable/package_esp8266com_index.json` in the 'Additional Board Manager URL' field and click 'Ok'.
3. Go to `Tools` -> `Board` -> `Boards Manager`. In the Boards Manager window, type `ESP8266` in the search box, select the latest version of the board, and click on `Install`.
4. After installation, go to `Tools` -> `Board` and select `NodeMCU 1.0 (ESP-12E Module)` to program the NodeMCU using Arduino IDE.

## Step 2: Assemble the Circuit

Assemble the circuit following the circuit diagram in the `circuit.jpg` attached to this sketch.

## Step 3: Load the Code

Upload the code provided in this sketch onto your NodeMCU board.

## Step 4: Hardware Requirements

| SN  | Part Name        |
| --- | ---------------- |
| 01  | NodeMCU (ESP8266)|
| 02  | Ultrasonic Sensor|
| 03  | Float Sensor     |
| 04  | GPS Sensor       |
| 05  | Red LED          |
| 06  | 10k Resistor     |

## Screenshots

![block](https://github.com/SuhailMuhammed1/Sewage-Monitoring-System-For-Blockage-Point-Detection/assets/104970300/aaf1604a-6815-465d-b919-9522767d1947) ![circuit](https://github.com/SuhailMuhammed1/Sewage-Monitoring-System-For-Blockage-Point-Detection/assets/104970300/c7089bab-d240-41d7-b404-7e1ba43ece77)

![overview](https://github.com/SuhailMuhammed1/Sewage-Monitoring-System-For-Blockage-Point-Detection/assets/104970300/e08d7c37-05f0-4d1c-8b78-8d67251d5542) ![alert](https://github.com/SuhailMuhammed1/Sewage-Monitoring-System-For-Blockage-Point-Detection/assets/104970300/83f72351-dd6a-461c-a8e9-1142c366ff31)

![6](https://github.com/SuhailMuhammed1/Sewage-Monitoring-System-For-Blockage-Point-Detection/assets/104970300/397b0f8d-ec6d-418c-847c-8e319cc53b49) ![8](https://github.com/SuhailMuhammed1/Sewage-Monitoring-System-For-Blockage-Point-Detection/assets/104970300/d624d9dd-ab8b-4f48-9634-e29c82d7dde7)


