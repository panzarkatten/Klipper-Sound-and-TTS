# Klipper-Sound-and-TTS
Some stuff to make klipper play sounds and speak tts through the rpi 3.5mm audio jack

Can only play .wav files. 

## Installation
Install the gcode_shell_command.py module to Klipper
 1. Download **gcode_shell_command.py** from https://github.com/th33xitus/kiauh/tree/master/resources
 2. Copy **gcode_shell_command.py** to ~\klipper\klippy\extras\
 3. Reboot Pi

### shell_commands
Setup of the shell commands used.

### play.sh
Basic bash script that just takes the first argument and runs aplay with that argument.

### macros.cfg
Example macros using the shell commands.