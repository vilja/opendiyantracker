This Antenna Tracker is Open Source and based in the Ardupilot code produced by Jordi Munõz and the AP Team. It has also portions of code written by Melih Karakelle and by Dennis Frie, both freely available  in the web.

It needs two arduino boards (arduino pro or other), and some more bits to adapt signals between Arduino and Video audio Tx and between video audio Rx and Arduino.

It just needs gps data (GPGGA and GPRMC, default to 38400bps) in the pin0(Rx) of the Arduino.

This code was bench tested, directly and using a Video RF link(Tx,Rx)  between Arduinos.

It was tested in the Rc field with success, see it here:

Pre-alpha version: http://www.youtube.com/watch?v=wZcKmu3GjjM

Alpha version: http://www.youtube.com/watch?v=m5C7Hacw6K0

It has now the tilt fully functional, see a 360 degrees turn around the base ground station:

http://www.youtube.com/watch?v=52BA7JhW1Ug&feature=channel&list=UL

It uses a 360 degrees PAN servo (a winch servo) and a regular TILT servo.  The Pan and Tilt rig could be home built (very easy!) or you can buy one ready to roll, your choice.

This code is not finished, this is version Tx\_02a/Rx\_01d (ALPHA), we need to  improve the Audio Link or evolve to the Video link to carry the telemetry (we could also improve the package mismatch dealing).

With time, I'll improve the wiki to help the newcomers to start with this Antenna Tracker with some photos and schematics (already done, check Connections and HowToUse tabs...).

I hope the RC community give their hands to this project and help develop it from here.  Sure there is much to do and to change ;-)