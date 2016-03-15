#New connections....
The pics are self explanatory, but here it goes:

# Tx Side #


http://opendiyantracker.googlecode.com/svn/images/Arduino_Tx_side_1.JPG
The orange wire carries the signal to the audio IN of your video Tx (black is ground and only connected in one side), the orange disk is a ceramic capacitor marked 473 (47nF) so far it is the value that works better.

EDIT: I am trying now this instead of the above (the above work well, but I notice some banding in the video, thus the change):

Pay attention to the audio level of the Arduino output in order to not saturate audio input of your video Tx.

Use a GND --1.8kOhm --|--8.2KOhm--pin10
> |
> audio Input


http://opendiyantracker.googlecode.com/svn/images/Arduino_Tx_side_2.JPG
Power from the lipo to the RAW pin of the arduino and also the ground (bear in mind common ground and ONLY effective connection to Ground -avoid ground loops-), the green wire brings the gps signal, in this case 9600bps, but you have to adapt t your gps unit change it in the code also).


http://opendiyantracker.googlecode.com/svn/images/Arduino_Tx_side_3.JPG
Fixed to the TS with double side foam.



# Rx Side #

New photo-schematic to follow:
http://opendiyantracker.googlecode.com/svn/images/OpenDiyAT_Rx_connections_small_2.JPG

http://opendiyantracker.googlecode.com/svn/images/OpendiyAT_servos_connections.JPG
Example of servo connections using a stripboard for simplicity and wire arrangement
PIN9 for PAN and PIN10 for TILT

http://opendiyantracker.googlecode.com/svn/images/Rx_input_schematic.JPG
The audio "adapter" schematic, borrowed from other modem project.


http://opendiyantracker.googlecode.com/svn/images/Rx_side_Arduino_inputFilter.JPG
Bench used filter.



http://opendiyantracker.googlecode.com/svn/images/Rx_side_Arduino_inputFilter_2.JPG
filter adapted to a pcb board.



http://opendiyantracker.googlecode.com/svn/images/ReadyToRoll.JPG
One winch servo for PAN (Servo GWS S125 1T de 360º or other) and a regular Futaba F148 (or equivalent)  for TILT.
All ready to roll.