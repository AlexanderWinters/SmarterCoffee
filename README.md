# Smarter Coffee
With this project I will attempt to smartify my coffee pot. The pot is a generic 10€ pot I found in a hardware store. It has a heating element connected directly to city power, and a minimal controller with a relay, a timer and a button. 

Components I used:
- Relay 240V 5A
- RPi pico W
- AC/DC converter 240V to 5V 2A

The relay is used to switch on and off the resistor. The pico is for remote controll and integration with Home Assistant. I used a single, premade component for converting and stepping down power. It includes the bridge, safeties, and surge protections needed so the pico doesn't explode. 
