# USB-StepDown
A buck converter + ldo that converts non power delivery USB (C to C compatible) to 3V3 and 1V8. 
Particularily useful for embedded development.

# Design Goals
I created this design so that I could test another board that required 3V3 and 1V8 inputs. (For use with PixArt PMW3360) Some of the key goals were for the pcb to be as compact as possible as I wanted to reuse portions of the schematic on other boards. I added schottky diodes at the expense of efficiency so that the board was not reliant on usb availability. This board can regulate up to 6v (~7v possible but not reccomended due to the LDO) to 3V3 and 1V8. The efficiency is not great due to the voltage drop of the diodes however this was not a priority for me as this board will only be used in a testing environment.

## Version History

V1 - Initial design (not on repository :( )

V1.1 - Fixed missing trace from feedback resistor to ground= and tidied up some trace paths.
