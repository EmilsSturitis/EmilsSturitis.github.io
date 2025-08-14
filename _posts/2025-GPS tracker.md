---
layout: post
title: GPS tracker for activity review
date: 2024-11-09
categories: blogging
tags: GPS, GNSS, activity
--- 
  
  
  
# Introduction

This will be the first post in the series where i will create a small GPS based activity tracker, covering from the conception of the idea, to the first tests with development boards to creation of final PCB, enclosure and data analysis tools.   

This kind of device has been on my mind since 2019 when i first participated in Rogainning competition, where each team had a GPS device so it could be monitored how the teams are doing and make sure that they are respecting rules of the race. When you are in the distance no devices which can tell you how much distance you have covered and show you you're exact location cannot be used. Only a tracker can be used for later review of you race and learn from your mistakes.  


# Project Concept and Requirements

The goal of this project is:  
    1. Device runtime for atleast 24h  
    2. Logging of data every second  
    3. Save data on sd memory card  
    4. Battery charging with USB connection  
    5. Setings and updating using USB connection  
    6. Additional sensors:  
        6.1. 6 axis IMU  
        6.2. Altimeter sensor  


# Schematic Design
## MCU and perephials

## IMU
The sensor used is Bosch BMI323 with I2C interface
![IMU circuit](/assets/images/GPS-tracker_1.png)

## Altimeter
The sensor used is TE MS580301-BA01-00.

![Altimeter sensor](/assets/images/GPS-tracker_2.png)
## Pushbuttons and leds

## Battery protection and charging
The IC used is TI BQ24072RGT. 
![Battery charging](/assets/images/GPS-tracker_3.png)

# PCB Layout
PCB Design: 
# Prototype Development
Assembly: were addressed by adding heatsinks.
# Software and Firmware (if applicable)
Firmware Development: 
# Enclosure Design
Mechanical Design: 
# Final Testing and Validation
Functional Testing: .
# Challenges and Lessons Learned
Challenges 
# Conclusion and Future Work
Summary: 
# Resources and References
Component Datasheets: Provide links to the datasheets of key components used in the design.
Tools and Software: Mention the tools and software that were particularly helpful during the design process.
Further Reading: Suggest books, articles, or videos for readers who want to learn more about the topics covered.
Example: Datasheets for the TP4056 charging IC and the chosen Li-ion battery can be found here.
