:Author: Suhail Muhammed
:Email: suhailjr111@gmail.com
:Date: 17/11/2022
:Revision: version#
:License: Public Domain

= Sewage Monitoring System For Blockage Point Detection

An Arduino sketch for Sewage Monitoring System For Blockage Point Detection. The system utilizes nodeMCU board, sensors, and the Arduino IoT Cloud to monitor distance, water level, and GPS coordinates. It features automated alerts and visualization of data on the IoT Cloud dashboard.

== Step 1: Installation
Install Arduino IDE 

1. Open File-->Preferences-->Settings.
2. Type https://arduino.esp8266.com/stable/package_esp8266com_index.json in the ‘Additional Board Manager URL’ field and click ‘Ok’.
3. Now go to Tools--> Board--> Boards Manager. In Boards Manager window, Type ESP8266 in the search box, select the latest version of the board and click on install.
4. After the installation is complete, go to Tools-->Board--> and select NodeMCU 1.0(ESP-12E Module). Now, you can program NodeMCU with Arduino IDE.


== Step 2: Assemble the circuit

Assemble the circuit following the diagram circuit.jpg attached to the sketch.

== Step 3: Load the code

Upload the code contained in this sketch on to your board

== Step 4: Hardware Requirements

|===
| SN | Part name      
| 01 | NodeMCU (ESP8266)        
| 02 | Ultrasonic sensor                
| 03 | Float sensor  
| 04 |  GPS sensor      
| 05 | Red LED                
| 06 | 10k Resistor          
|===

