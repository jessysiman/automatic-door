# Automatic door
The components used in this project are the ATMega8-16P microcontroller, the
TSSP58038 infrared sensor, two LEDs, the L298 motor driver, batteries and socket, a dc-motor,
and a couple of resistors, capacitors, and a 16MHz crystal. This system works by first having the
infrared sensor detect any signs of an object near the system. Afterwards, the sensor sends the
analog signal to the ATMega8 microcontroller for it to process it. If there is an object/living
being detected, the ATMega8 will tell the motor driver to rotate the dc-motor counterclockwise
to open the door. Then, when there is no object detected for around 5 seconds, the motor driver
will have the dc-motor rotate clockwise to close the door. Additionally, there are also LEDs that
will signify if the door is opened or closed.
