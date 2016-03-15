# Introduction #

A breve description of how to use this OpenDiyAT

# Details #

http://opendiyantracker.googlecode.com/svn/images/OpenDiyAT_Rx_connections_small.JPG

Mark the neutral of your antenna tracker (winch servo in neutral position).

Face the antenna to the centre of "the window" of flight you usually use in your rc field or center the antenna in the direction you pretend to fly your model.

Carry your model and put it about 20 to 30m away from the ground station and in the centre of your "window", return to the ground station.

Check the direction to which the antenna is pointing, now press the button (this will make the software assume the centre of your window (or the direction you want to use).

Now, CAREFULLY, point the base of your antenna tracker (ALL, antenna + servos + base + wires, EVERYTHING) to the position of your model (remember, it is placed 20~30m away from the base and in the centre of your window).

Go get your model and return to your ground station.  Check to see if the antenna follow your model in your hands.

If it does, grab your RC Transmitter, check the commands and launch the model.

If not, re-do all of the above!

Bear in mind that the gps isn't accurate when you move with your model in your hands, you have to run in order to help the gps unit feed reasonable data to your arduino on-board, so when you return to the base is normal to see some indecision of your tracker, but it should follow you and increase tilt as you approach your base station.

# TheLedFuncion #

The Led have a double function.

It lights in the beginning till the Arduino in the model receive good data from the gps unit and transmit it to the Arduino in the Antenna tracker and this establishes a HOME position - led off-

From now on, whenever the led lights up, the Arduino in Tracker received a corrupted package, this happen whenever the audio link is disrupted with noise.

If the led is continuously illuminated, then you have a problem, Home not set or total disruption of the audio link (this could led to a rebooted arduino or halted arduino)

