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