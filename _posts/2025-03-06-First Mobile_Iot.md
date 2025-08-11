---
layout: post
title: Entery to Mobile Iot
date: 2025-03-06
categories: blogging
tags: GPS, GNSS, activity
--- 
  
  
  
# Introduction

NRF 9151

# Project Concept and Requirements

The goal of this project is:  
    1. Use the available resorces to create a simple tracker to display the location on a dashboard. 


# Schematic Design
## MCU and perephials

## IMU
The sensor used is Bosch BMI323 with I2C interface
![IMU circuit](/images/GPS-tracker_1.png)

## Altimeter
The sensor used is TE MS580301-BA01-00.

![Altimeter sensor](/images/GPS-tracker_2.png)
## Pushbuttons and leds

## Battery protection and charging
The IC used is TI BQ24072RGT. 
![Battery charging](/images/GPS-tracker_3.png)

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

hakster post: https://www.hackster.io/piyareraj/how-to-connect-and-visualize-iot-data-using-datacake-cloud-2f6681
