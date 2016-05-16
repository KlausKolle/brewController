# brewController
BeagleBone Black C++ application for controlling a brew tun

It will monitor wort temperature using a DS18B20 one wire temperature sensor. Using a PID controller it will control a 1,8 kW electric heating element - or rather a relay that turns on and of the heating element.

Together with brewWeb, the client part, you can set recipes and monitor the progress of your brew in nice graphical presentations, althoug the design has not been my main issue.
