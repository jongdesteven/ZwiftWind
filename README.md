# ZwiftWind
Powerful fan controlled by esphome for Zwift based on a 12V Car fan

## Used
- 180W 12V DC Car fan from Audi 80 (Febi Bilstein 18780)
  - Because it was high power, DC 12V and pretty Cheap.
- 12V 20A LED power supply
- Mosfet board from 3D printer hotbed controller (12V 30A)
  - Only used the mosfet + heatsink, desoldered the MOSFET from the other components.
- ESP32 module 
  - Chosen over esp8266 for higher PWM frequency (LEDC pin)
- DC-DC converter 12V - 3V3 for powering the ESP32
- Schottky Diode for flyback
- BC557(PNP) + BC547(NPN) Transistors
- 2x 1K resistor + 1x 150 resistor

## Schematic Drawing
![Circuit](/circuit.png)

