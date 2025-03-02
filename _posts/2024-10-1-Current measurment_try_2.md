---
layout: post
title: Non-contact current sensing
date: 2024-10-05
categories: blogging
tags: Current sensing, current measurment, hall sensors, shunt, GMR, TMR
---

## Introduction
Purpose of the Project: To create a non-Contact current measurment device, so current waveforms could be measured without nodifying circuits.
## Research and Planning
### Market Research: the two devices which i wanted to compete with
#### AIM-TTI i-probe 520: small size non contact current measurment brobe based on the Fluxgate magnotometer.
(picture)
#### Little Bee by Weston Braun: AMR based current sensor with extenal concentrator 
(picture)
### Component Selection: 
Sensor used Honeywell HMC1051
## Schematic Design
Circuit Design: Based on the HMC1051 datasheet and application notes by Honeywell. 
The basic bloks are: bridge sensor measurment part and set/reset circuit
### Sensor connection

### Set/Reset 

## PCB Layout
PCB Design: Show the PCB layout and discuss the considerations for component placement, trace routing, and thermal management.
Manufacturing Constraints: Mention any design decisions influenced by the manufacturing process, such as trace width, via size, or board layer count.
Example: The PCB layout was designed to minimize the footprint while ensuring good thermal management for the power components.
## Prototype Development
Assembly: Describe the process of assembling the prototype, including soldering components and any challenges faced.
Testing and Debugging: Outline the testing process, highlighting how you verified the functionality of the device and any issues encountered.
![Rendered device](/images/cm_2.png)
![Assembled device](/images/cm_1.jpeg)
Example: After assembling the prototype, we tested it with various devices to ensure stable output voltage and current. Some issues with heat dissipation were addressed by adding heatsinks.
## Final Testing and Validation
Functional Testing: Summarize the results of the final testing phase, including any real-world usage scenarios.
Performance Metrics: Provide data on key performance metrics, such as battery life, charging time, efficiency, and thermal performance.
Example: The final prototype successfully charged a smartphone from 0% to 100% three times on a single charge, with a measured efficiency of 85%.
## Challenges and Lessons Learned
Challenges Faced: Reflect on the challenges encountered during the project, such as technical issues, design revisions, or unforeseen difficulties.
Lessons Learned: Share insights gained from the project, including what worked well and what could be improved in future iterations.
Example: One of the biggest challenges was managing heat dissipation in a compact design. In future versions, I would explore using a metal enclosure to improve heat management.
## Conclusion and Future Work
Summary: Recap the project, highlighting the key takeaways and the overall success of the design.
Future Improvements: Suggest possible improvements or additional features that could be added in future versions of the device.
Example: Overall, the custom power bank met the design objectives, but in future iterations, I would focus on reducing the overall size and improving charging speed.
## Resources and References

 [Weston Braun Github](https://github.com/westonb/little-bee-B1)

## Tags and Categories
Tags: Use relevant tags like electronics, DIY electronics, PCB design, prototyping, etc.
Categories: Place the post in a category such as Electronics Projects or Design Guides.
