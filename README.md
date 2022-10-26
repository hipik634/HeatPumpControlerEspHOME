# Heat Pump Controller EspHOME
heat pump controler open esphome at esp8266

#inspiration https://github.com/openhp/HeatPumpController/
#no EEV module yet/no need on my side, got TXV
#meant to be used standalone with HA as an option to visualize, display 

place all 7 basic sensors all around units, 4 internal, 3 external

uses standard bang-bang thermostat control

on startup it rises safety pin to disable all AC220V stuff

it checks temp sensors to tell if conditions are ok

if temp is lower then preset, it starts the script - enables fan, compressor and 4 way valve to start heat pump

draws all to HAOS (Home Assistant)




