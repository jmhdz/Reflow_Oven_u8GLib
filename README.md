Arduino sketch to control a Toaster oven reflow oven.

Features:

3 different profiles can be programmed (leaded, leadfree and drying) allows flexibility
Just 3 action buttons (single buttons press needed to start a profile - no menus, easy to use) + Reset button

Option to use
- EPCOS B57540G1104F000 Thermistor (Reprap style circuit with 4K7 pullup)
- MAX6755 Thermocouple Amplifier
- Even a DS18B20 (NOTE  Not suitable with average reflow temps - but I added it since i intend using one of these (slightly modified UI) on another application where a DS18B20 would be perfect

![Reflow Controller](https://raw.githubusercontent.com/openhardwarecoza/Reflow_Oven_u8GLib/master/Photo/20151103_145121.jpg)

Based on code from:  
http://reprap.org/wiki/Temperature_Sensor_v1.1#Upload_firmware_to_Arduino

http://reprap.org/wiki/Toaster_Oven_Reflow_Technique

https://github.com/adafruit/MAX6675-library

http://playground.arduino.cc/Learning/OneWire

https://github.com/olikraus/u8glib/wiki
