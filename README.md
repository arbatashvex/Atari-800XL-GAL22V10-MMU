# Atari-800XL-GAL22V10-MMU
If you don't have a GAL16V8 chip to program for MMU, Here you can use GAL22V10. Pins rearanged based on Bob Woolley's file.

Here you can find an original JED file from Bob Woolley for MMU for atari 800XL as well as the adapted file for GAL22V10.

Since GAL22V10 is larger by 4 pins, minor adaptations should be made.

You program it normally. 
When installing, you should lift pin 10 (since it is groun on the motherboard) and left it hanging.
You should connect or solder a wire from ground to the pin 12 of the GAL22V10 chip. 10 pins that are in the socket work as the original MMU and 4 pins are left hanging outside. 
