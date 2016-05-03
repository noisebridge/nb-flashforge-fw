Noisebridge Flashforge Firmware
===============================

May, 2016
Copy of firmwares and config informatoin for the Flashforge 3D printer at Noisebridge

Capture the firmware with avrdude and an avr programmer (used a dragon avr) 
````	
miloh@box~$ avrdude -c dragon_isp -p m1280 -U flash:r:flashforge.bin:r
avrdude: jtagmkII_getsync(): sign-on command: status -1
avrdude: jtagmkII_getsync(): sign-on command: status -1

avrdude: AVR device initialized and ready to accept instructions

Reading | ################################################## | 100% 0.15s

avrdude: Device signature = 0x1e9703
avrdude: reading flash memory:

Reading | ################################################## | 100% 60.30s

avrdude: writing output file "flashforge.bin"

avrdude: safemode: Fuses OK (E:FD, H:DA, L:FF)

avrdude done.  Thank you.
````
