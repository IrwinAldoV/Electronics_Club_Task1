# Drowsiness  Detector

## Description

This project focuses on creating a machine-learning based fatigue/Drowsiness detection system, It helps in preventing road accidents caused due to fatigue/Drowsiness of the driver, These kind of accidents are more common in Highways.


In this project, we will have a manual input box consisting of 3 states-Left, Right, and Straight. And This input given by the rider is of first priority.
In case the rider is not providing us with the input, the power of automation comes into action,
The orientation of the cycle's handle(in degrees) is calculated with the help of a variable resistor. Depending upon the value of the resistance, the angle of turn is calculated, and with this value, the system decides to which state it belongs-Left, Right, and Straight.
Now the value of states is continuously fed to our output module via the BlueTooth module.

Upon receiving this value of states, The output module first checks whether there is a change in the state or not. If there is a change, The output module decides to display the pre-assigned set of outputs i.e., audio and visual output.
The visual output is an arrow indicating the direction of the turn, which is displayed with the help of an LED matrix, along with the audio output produced by the sound module, telling the fellow pedestrians and the rides about the direction in which you are turning.
This project helps in preventing accidents due to uninformed changes in the direction of the vehicles.


Hardware Components:
      
    Infineon PSoC™ 62S2 Wi-Fi BT Pioneer Kit
    Infineon IoT Sense Expansion Kit
    Seeed Studio ESP32-CAM Development Board
    Jumper wires
    
Softwares Used:

    Infineon ModusToolbox™ Software
    Arduino IDE

## Circuit Diagrams:
![](https://hackster.imgix.net/uploads/attachments/1456247/schematic_qC8jHDAgjo.png?auto=compress%2Cformat&w=740&h=555&fit=max)

## Project GIF:
![](https://hackster.imgix.net/uploads/attachments/1455903/download_bYjXRS1DqP.gif)
![](https://hackster.imgix.net/uploads/attachments/1450755/15379999-c327-4a56-9f1c-5e238edc080d_MegHn64GHa.jpeg?auto=compress%2Cformat&w=740&h=555&fit=max)

The web link for the detailed description of the project: [Drowsiness Detector](https://www.hackster.io/AkuG1802/driver-fatigue-detector-9cb688)
