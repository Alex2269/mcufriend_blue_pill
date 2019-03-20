
``` cpp
# stm32_blue_pill_tft

http://wiki.stm32duino.com/index.php?title=Blue_Pill

original lib:
https://github.com/prenticedavid/MCUFRIEND_kbv

depends:
https://github.com/adafruit/Adafruit-GFX-Library

file connections - mcufriend_shield.h
See pcb directory for connections.
Changes only connections tft display with shift of pins:

 0 1 2 3 4 5 6 7 mcu
 | | | | | | | |
 2 3 4 5 6 7 0 1 tft
 

 ```
