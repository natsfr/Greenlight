# GreenLight
## What is it ?
Greenlight is opensource growing plant system. It's made to be simple and used in small cabinet.

## Hardware
The system has many board:
* one motherboard with the ESP32 and env sensor (moisture, light, CO2, temperature, ...).
* one or many LED board (each board has either Blue and Red Leds, or a White light)
### Main IC
#### Main Board
* Controller: ESP32 WROOM
* RTC: DS1302SN+
* CO2 Sensor: https://www.reichelt.com/fr/fr/sonde-co2-infrarouge-mh-z19c-t-te-de-broche-rm-2-54-co2-mh-z19c-ph-p297320.html


#### Led Board
* SMPS: L6982NDR -> 2A 38V buck converter
* LED Driver: ADP8140 -> 4 Channel 500mA
* Red LED: MLERED-A1-0000-000U01 -> 350mA 2.4V
* Blue LED: MLEBLU-A1-0000-000T01 -> 350mA 3.2V