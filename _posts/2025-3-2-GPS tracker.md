---
layout: post
title: GPS tracker for activity review
date: 2024-09-11
categories: blogging
tags: GPS, GNSS, activity
--- 
  
  
  
# Introduction

This will be the first post in the series where i will create a small GPS based activity tracker, covering from the conception of the idea, to the first tests with development boards to creation of final PCB, enclosure and data analysis tools.   

This kind of device has been on my mind since 2019 when i first participated in Rogainning competition, where each team had a GPS device so it could be monitored how the teams are doing and make sure that they are respecting rules of the race. When you are in the distance no devices which can tell you how much distance you have covered and show you you're exact location cannot be used. Only a tracker can be used for later review of you race and learn from your mistakes.  


# Project Concept and Requirements
Problem Statement: Define the problem that your device aims to solve or the need it fulfills.  
Target Audience: Identify who the device is for and any specific needs they might have.
Design Objectives: List the key objectives, such as size, power capacity, efficiency, portability, or cost.
Example: The goal is to design a compact, lightweight power bank capable of charging smartphones and tablets with a capacity of at least 10,000mAh.


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
![IMU circuit](/images/GPS-tracker_1.png)

## Altimeter

## Pushbuttons and leds

## Battery protection and charging


# PCB Layout
PCB Design: Show the PCB layout and discuss the considerations for component placement, trace routing, and thermal management.
Manufacturing Constraints: Mention any design decisions influenced by the manufacturing process, such as trace width, via size, or board layer count.
Example: The PCB layout was designed to minimize the footprint while ensuring good thermal management for the power components.
# Prototype Development
Assembly: Describe the process of assembling the prototype, including soldering components and any challenges faced.
Testing and Debugging: Outline the testing process, highlighting how you verified the functionality of the device and any issues encountered.
Example: After assembling the prototype, we tested it with various devices to ensure stable output voltage and current. Some issues with heat dissipation were addressed by adding heatsinks.
# Software and Firmware (if applicable)
Firmware Development: Discuss any firmware or software developed for the device, such as a microcontroller program to manage charging/discharging.
User Interface: If the device includes a user interface (e.g., LED indicators, display), explain its design and functionality.
Example: We developed firmware for an ATtiny85 microcontroller to monitor battery voltage and control the charging process.
# Enclosure Design
Mechanical Design: Describe the process of designing the enclosure, including material selection and methods used (e.g., 3D printing, CNC machining).
Aesthetics and Ergonomics: Discuss the design considerations for the look and feel of the device, such as portability, durability, and user comfort.
Example: The enclosure was 3D-printed using ABS plastic, chosen for its durability and heat resistance. The design was kept sleek and compact to enhance portability.
# Final Testing and Validation
Functional Testing: Summarize the results of the final testing phase, including any real-world usage scenarios.
Performance Metrics: Provide data on key performance metrics, such as battery life, charging time, efficiency, and thermal performance.
Example: The final prototype successfully charged a smartphone from 0% to 100% three times on a single charge, with a measured efficiency of 85%.
# Challenges and Lessons Learned
Challenges Faced: Reflect on the challenges encountered during the project, such as technical issues, design revisions, or unforeseen difficulties.
Lessons Learned: Share insights gained from the project, including what worked well and what could be improved in future iterations.
Example: One of the biggest challenges was managing heat dissipation in a compact design. In future versions, I would explore using a metal enclosure to improve heat management.
# Conclusion and Future Work
Summary: Recap the project, highlighting the key takeaways and the overall success of the design.
Future Improvements: Suggest possible improvements or additional features that could be added in future versions of the device.
Example: Overall, the custom power bank met the design objectives, but in future iterations, I would focus on reducing the overall size and improving charging speed.
# Resources and References
Component Datasheets: Provide links to the datasheets of key components used in the design.
Tools and Software: Mention the tools and software that were particularly helpful during the design process.
Further Reading: Suggest books, articles, or videos for readers who want to learn more about the topics covered.
Example: Datasheets for the TP4056 charging IC and the chosen Li-ion battery can be found here.
