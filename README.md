# ESPHOME-Sensor2

The [first Sensor](https://github.com/WaarlandIT/ESPHOME-MMW) was just a test but this one is really usefull.

A mm wave sensor is sometimes too slow in detecting a person entering the room, adding a PIR sensor solves that issue.
Because I had some Arduino sensors unused in a box I added the DH2 sensor. The DH2 sensor reads temprature and humidity. 

Also the first sensor was batery powered, that did not last long so this one is powered by USB.

## Diagram of how it is all connected
![Sensor2-mmw-pir-dh](https://github.com/WaarlandIT/ESPHOME-Sensor2/assets/53364386/c5739d2d-0919-46cc-8d0e-b5ee6c688b18)

The ESP-01 and the DH2 need both a pull up resistor. I used for the ESP-01 a 100k resistor and for the DH2 a 10k resistor.
