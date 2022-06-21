# Automatic Vehicle indication system  

## Description

This project focuses on building an automated indication system for non-motor vehicles like bicycles.
The output of this project is a direction arrow that is to be displayed on the LED matrix along with the audio.

In this project, we will have a manual input box consisting of 3 states-Left, Right, and Straight. And This input given by the rider is of first priority.
In case the rider is not providing us with the input, the power of automation comes into action,
The orientation of the cycle's handle(in degrees) is calculated with the help of a variable resistor. Depending upon the value of the resistance, the angle of turn is calculated, and with this value, the system decides to which state it belongs-Left, Right, and Straight.
Now the value of states is continuously fed to our output module via the BlueTooth module.

Upon receiving this value of states, The output module first checks whether there is a change in the state or not. If there is a change, The output module decides to display the pre-assigned set of outputs i.e., audio and visual output.
The visual output is an arrow indicating the direction of the turn, which is displayed with the help of an LED matrix, along with the audio output produced by the sound module, telling the fellow pedestrians and the rides about the direction in which you are turning.
This project helps in preventing accidents due to uninformed changes in the direction of the vehicles.


Circuit Components
      
    Arduino UNO
    Jumper wires 
    Speaker, Piezo	
    Digilent Voltage Regulator Module
    Arduino Wireless SD Shield
    Flash Memory Card, SD Card	
    Programmable Soft LED Board
    Li-Ion Battery 1000mAh	
    HC-05 Bluetooth Module	
    synchronizing line
    Bike Holder
    Alligator clip & rope
    
Softwares Used:
       
    Arduino IDE
    AutoCAD(in designing phase)

## Circuit Diagram
![](https://www.electronicshub.org/wp-content/uploads/2014/06/Auto-Intensity-Control-of-Street-Lights-Circuit-Diagram-768x367.jpg)

The web link for the detailed description of the project: [Auto Intensity control of Street lights ](https://www.electronicshub.org/auto-intensity-control-of-street-lights/)
