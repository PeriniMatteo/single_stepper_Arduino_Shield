# single_stepper_Arduino_Shield
###This repository contains schematics to build an Arduino shield that use grbl firmware and a single Pololu A4988 stepper driver on Z axis

***

This project is under GPL V3 license (see the LICENSE file for more informations)

***

**Shematics are fzz file that you can open with [Fritzing](http://fritzing.org/home/)** 

>"Fritzing is an open-source hardware initiative that makes electronics accessible as a creative material for anyone" 

**To manage a stepper motor you will need a running firmware on your Arduino board!**

You can find the last version of grbl code here: [grbl](https://github.com/grbl/grbl)

To flash grbl into Arduino directly you can follow these steps:

+ Download and extract the last grbl version 
+ From Arduino Ide select in the menu Sketch -> #include library -> add library from ZIP (this will work with folder too) 
+ Navigate to the unzipped grbl-master folder and select the sub-directory "grbl"
+ Now your Arduino Ide will be able to use the new library 
+ From the menu File -> example -> grbl select the file "grblUpload" 
+ Compile it and flash on your Arduino board

Sending a valid Gcode through serial to the Arduino you will be able to control with high precision a stepper motor

