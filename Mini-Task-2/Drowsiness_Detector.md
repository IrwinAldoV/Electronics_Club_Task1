# Drowsiness  Detector

## Description

This project focuses on creating a machine-learning based fatigue/Drowsiness detection system, It helps in preventing road accidents caused due to fatigue/Drowsiness of the driver, These kind of accidents are more common in Highways.

In this project we are going to run our trained ML model on a embedded system, [ModulusToolBox](https://www.infineon.com/cms/en/design-support/tools/sdk/modustoolbox-software/?utm_source=cypress&utm_medium=referral&utm_campaign=202110_globe_en_all_integration-product_families) software provides an easy and interactive way to transform the Keras model file into an embedded C++ library, The Seeed Studio ESP32-CAM Development Board is used to get input in form of camera frames, these frames are then continuously sent to the ML model to decide whether the driver is alert or drowsy, Based on this, if the driver is found to be drowsy, then LEDs will blink non-stop until the user becomes alert, and also a voice altert asking the driver to stop driving and to take rest, This process occurs in a continuous loop.




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
![](https://hackster.imgix.net/uploads/attachments/1455903/download_bYjXRS1DqP.gif?auto=compress&gifq=35&w=740&h=555&fit=max)


Link of the project: [Drowsiness Detector](https://www.hackster.io/AkuG1802/driver-fatigue-detector-9cb688)

Link of the workings: [Working-Video](https://youtu.be/hJ4yNnr62P8)
