Mega 🔥
A simple home automation project using Arduino Mega, a sound sensor (KY-038), and a 5V relay module to control a 7W AC LED bulb with a clap.

🔧 Features:
✅ Clap to turn the light ON/OFF
✅ Uses a 5V relay module to handle AC power
✅ No resistors or breadboard required
✅ Works with any standard LED bulb

🛠 Components Required:
Component	Description
Arduino Mega	Microcontroller
KY-038 Sound Sensor	Detects claps
5V Relay Module	Controls AC bulb
7W AC LED Bulb	Light source
Wires & Power Supply	For connections
🔌 Circuit Diagram & Connections:
Sound Sensor to Arduino Mega:
VCC → 5V
GND → GND
OUT → Digital Pin 2
Relay Module to Arduino Mega:
VCC → 5V
GND → GND
IN → Digital Pin 7
AC 7W Bulb to Relay Module:
Bulb Live Wire → COM (Common) on Relay
Bulb Neutral Wire → Direct AC Power
Relay NO (Normally Open) → AC Power Live
