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

## Circuit Diagrams:
![](https://hackster.imgix.net/uploads/attachments/1450753/70ad09b4-dd83-4c36-938d-18427fb609f4_9ZzcqzwTgO.jpeg?auto=compress%2Cformat&w=740&h=555&fit=max)
![](https://hackster.imgix.net/uploads/attachments/1450754/8c2cd617-ce4b-4e1e-973e-4c2879870e63_QjJ65aHplK.png?auto=compress%2Cformat&w=740&h=555&fit=max)
![](https://hackster.imgix.net/uploads/attachments/1450755/15379999-c327-4a56-9f1c-5e238edc080d_MegHn64GHa.jpeg?auto=compress%2Cformat&w=740&h=555&fit=max)

The web link for the detailed description of the project: [Automatic Vehicle indication system](https://www.hackster.io/andyz1207/automated-bike-turning-light-374f81)
