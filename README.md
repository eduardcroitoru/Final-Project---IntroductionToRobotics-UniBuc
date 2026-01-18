# Final-Project---IntroductionToRobotics-UniBuc

Remote-controlled rover where both the rover and the remote are Arduino-based.
The remote sends the input through Wi-Fi, then the signal gets picked-up by the rover.

# Bill of materials:
- breadboard x2
- Arduino Uno x2
- joystick
- Wi-Fi module
- servomotor
- resistors
- cables

# Tutorial source:
[Here](http://bit.ly/3NmuvS7).  

# Concept:
The rover board picks up the signal sent by the remote and acts accordingly.  
The computing part will be done mostly by the rover board.  
Communication and calibration are going to pose the biggest challenges.  
The minimum demo will be a rover that can only go forward and backward at a set speed.  
My build will be different from the one presented in the tutorial and will use a custom Arduino-based remote instead o a smartphone app.  
No need for an ESP32-based board.  
