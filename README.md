# HP-71B-JMOONS
HP-71B BASIC program to display the positions of the Galilean moons of Jupiter

This program produces a graphic display of the Galilean moons of Jupiter, with a "cursor" that is used to identify each of the moons.

It uses functions from the HPILROM and the JPCROM. 

To use, load the program, and invoke with "CALL JMOONS". You will be prompted for a date and time and offset from GMT. By default the current date and time is used, and the GMT offset is +5 hours (appropriate for US EST). To adjust the default GMT offset for your location, edit line 80.

Upon pressing ENDLINE, the display will show a large dot in the center of the screen, which represents Jupiter, and up to four dots on either side, which represent the moons. (NOTE that if one or more moons are immediately in front of or behind Jupiter, that moon (or moons) will not appear as a separate dot.) There is also a dot at the very bottom of the screen which is a "selector" -- it starts out under Io, and the flag 1 annunciator on the right side of the screen reflects that Io (also denoted "I") is the currently "selected" moon. The up and down arrow keys will cycle the "selector" through Europa (II), Ganymede (III), and Callisto (IV). The flag annunciators will update to reflect the currently selected moon. The left and right arrow keys will move the "selector" to the visually adjacent moons. At any time, you can press ENDLINE (or SPC), and the currently selected moon's name will be shown. Press ENDLINE (or SPC) again to return to the graphic display. Press RUN (or ON/ATTN) to end the program; the graphic display will remain until another key is pressed.
