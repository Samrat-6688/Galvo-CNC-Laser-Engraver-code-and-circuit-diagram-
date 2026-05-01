# Galvo-CNC-Laser-Engraver-code-and-circuit-diagram-
In this project the laser traces some shapes or any input we give to the machine.Components used in this project are :-
1. NEMA-17 Stepper motors 
2. Arduino Uno R3 
3. CNC V3 Arduino Shield 
4. Jumper Wires {F to F}
5. HW-493 laser module (For prototyping)
6. 3d Printed Body for mounting motors,laser,etc. 
7. 2 mirrors for reflecting the laser beam on the workspace 
8. 2x A4988 motor drivers for Nema-17's motors 
9. 12v power supply or battery pack for energiging motors

Circuit connection :- 
1. Mount the CNC shield on Arduino 
2. Place the A4988 drivers on the CNC shield on X and Y. And also place the heatsink on the black chip present on A4988 driver 
3. Now configure the wires of motors and connect them to connector header beside the A4988 divers.
4. Connect the power supply to the blue connector on CNC shield.[You have to screw the wires positive terminal and negative terminal.] !CAUTION! check the polarity of powersupply and the blue connector or else the motor will get burned.
5. Connect the Laser module [HW-493] on the pin D12 of the signal pin of the laser module, connect the GND pin of laser module to GND on shield, connect the VCC pin of laser module to 5v on CNC sheild. 
6. Now upload the code in the arduino using Arduino IDE. 
# Thats all we have done everty thing of technical now we have to look after the placement of mirrors and laser module. 
1. Stick the mirors to the motors, turn on laser and do the changes accordingly.
2. The laser should point on Workspace. 
Thats all , now we have to open serial monitor on Arduino Ide and set the baud rate to 9600 and then type 1, then type S for tracing Square.
## Done ! what a beautifull project!!!
