# Arduino Temperature & Humidity Monitor

Simple Arduino-based temperature and humidity monitor using a KY-015 (DHT11) and OLED display.

## Features
- Auto switching between temperature and humidity
- Button toggle between Fahrenheit and Celsius
- Clean centered display

## Wiring
OLED:
GND -> GND
VCC -> 5V
SDA -> A4
SCL -> A5

Sensor:
VCC -> 5V
GND -> GND
Signal -> D2

Button:
D3 -> Button -> GND

## Notes
- Sensor updates every ~2 seconds
- OLED address may be 0x3C or 0x3D
