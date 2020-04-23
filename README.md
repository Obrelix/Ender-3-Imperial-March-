# Ender-3-Imperial-March-


 [![Watch the video](https://i.imgur.com/KWxv6zv.png)](https://youtu.be/fOcZKwsDDqY)
 

Two GCode files that make the 3d printer to play the Imperial March. 

The above gcode files work on the 3d printer Creality Ender 3 that uses the MARLIN frimware.

The  **E3_Imperial_March.gcode**  file uses the  **G1** command that adds a linear move , with a specific rate,  to the queue to be performed after all previous moves are completed. By changing the rate and the posision of the stepper mottors produce frequencies for a certain period of time at specific times. **Reference :** [MARLIN Documentation G0-G1 Commands](https://marlinfw.org/docs/gcode/G000-G001.html)

The  **E3_Imperial_March_Buzzer.gcode**  file uses the  **M300** command that add a tone to the tone queue and its requires **SPEAKER** to play tones (not just beeps). **Reference :** [MARLIN Documentation M300 Command](https://marlinfw.org/docs/gcode/M300.html)

