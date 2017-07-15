# PIC16-PIR-motion-detector


This project includes code for PIR-motion-detector which uses PIC16LF1459 microcontroller. 
The microcontroller is in a sleep mode, and you can wake him up with IOC pins. These pins are connected
to the comparator outputs of PIR-motion-detector. When motion occur in front of PIR sensor, the microcontroller is being waked up. After that microcontroller sends information about motion via nRF24L01+ module to the server.
