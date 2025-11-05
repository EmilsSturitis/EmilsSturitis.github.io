---
layout: post
title: Loadcells and benchpress
date: 2025-08-01
categories: blogging
tags: Loadcell, HX711, activity
--- 
  
  
 ![Loadcell Benchpress](/assets/images/ChatGPT Image 2025. g. 8. sept. 23_06_28.png) 
# Introduction

Have you wondered what is your 1RM on benchpress? What is your 1RM vs grip width?
What is your max force on different distance from bar to chest?
I have spent countles sleeples nights thinking about this. How hard can it be to measure the force applied to a barbell?

# Project Concept 

# Project Requirements

The goal of this project is:  
    1. Measure force/wheigh applied to the barbell  
    2. Graph the data to a app on phone or PC  
    3. Perform calibration and offset calibration  
    4. Work from external power supply 

# Proof of concept build:
Needed to create a simple test setup to understand if ordered loadcell will be able to measure the needed force. 
### Circuit
ESP32 module and HX711 Loadcell converter
### Mechanical
Connection to barbell bench to loadcell and to barlbell
### App

### Device in operation


# Schematic Design
## MCU and perephials

## IMU
The sensor used is Bosch BMI323 with I2C interface
![IMU circuit](/assets/images/*.png)

## Altimeter
The sensor used is TE MS580301-BA01-00.

![Altimeter sensor](/assets/images/*.png)
## Pushbuttons and leds

## Battery protection and charging
The IC used is TI BQ24072RGT. 
![Battery charging](/assets/images/*.png)

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
