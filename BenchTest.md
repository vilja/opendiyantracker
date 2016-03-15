#Bench Test procedure.

# Introduction #

We can use  a ftdi cable to feed gps sentences to the arduino functioning as Tx or a gps receiver


# using a ftdi cable to feed gps sentences through a gps emulator #

http://opendiyantracker.googlecode.com/svn/images/Wired_ftdi_gps_source.JPG
(note: the extra wires are from a different project, don't consider them for this project.)


ftdi (tx pin) ---wire--->arduinoTx (Rx or pin 0)

arduinoTx (pin 10)----wire---> arduinoRx(pin 2)

All powered by usb connections.


As gps emulator (HappyKillmore's, NMEAGEN or google it) and as serial monitor (realterm, putty or google it)

The gps emulator use the ftdi usb port number, and the serial monitor use the usb port of the Arduino Rx



# using a gps receiver unit connected to the arduino Tx unit #

http://opendiyantracker.googlecode.com/svn/images/Wired_test_gps_Rx.JPG