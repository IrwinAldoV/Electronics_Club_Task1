# Threshold Alerting Device

## Description

In this project we are going to send notification to the user's mobile phone via SMS if the temperature of the surrounding crosses or goes out of a desired range.
Here we are using ESP32 as the controll board, Here we going to provide a desirable temperature range as the input provided that it is in the measuring range of the temperature sensor we are going to use.
We are going to measure the temperature of the surrounding using DS18B20 temperature sensor we are going to get the value from sensor and process it with the help of ESP32.
If the temperatue goes out of our desired range we are going to send an alterting message to the user's mobile number (that as been given to us earlier) using a Nano SIM card(which has be to in service).




Hardware Requirement:

    Nano SIM card with SMS plan
    TTGO T-Call ESP32 SIM800L 
    USB-C cable
    DS18B20 temperature sensor   
    4.7k Ohm resistor
    Breadboard
    Jumper wires 

Sotware(s) Used:

    Arduino IDE
    
Extra Libraries required(In Arduino IDE):
    
     TinyGSM
     DallasTemperature
     

## Circuit Diagram 

![](https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2019/09/ESP32-SIM800-with-DS18B20-schematic.png?w=761&quality=100&strip=all&ssl=1)


![](https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2019/09/Project-overview-for-post-send-SMS.png?quality=100&strip=all&ssl=1)

Link of the video : [Threshold Alerting](https://youtu.be/VM-viZHZvAs)

The link for the project: [Threshold Alerting Device](https://randomnerdtutorials.com/esp32-sim800l-send-text-messages-sms/)
