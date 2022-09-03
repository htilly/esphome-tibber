**WORK IN PROGRESS**

Quick hack to get Tibber data displayed on a small LCD display.

![Tibber LCD Display](https://github.com/htilly/esphome-tibber/blob/main/ESPHome-Tibber.png?raw=true)


*Prerequisite*  
HomeAssistant installation =)  
ESPHome enabled  
Tibber subscription..  Also, for the second page a Watty or Pulse is required.

*Hardware required*  
ESP32 unit.  
Small LCD display (https://esphome.io/components/display/ssd1306.html)

*Box*  
.stl files in the repo.

Note, the box was made based on the ESP32 board and LCD I currently had at home.
Improvements can be made =)

For 3D printing, see the following page for details:
https://www.tinkercad.com/things/0NzYibxJSMh-ledinfobox

In the tibber-display.yaml, find the device name of your tibber integration in HA and replace the values.
