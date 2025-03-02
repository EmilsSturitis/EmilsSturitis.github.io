---
layout: post
title: Current sensing try NR 1
date: 2024-09-05
categories: blogging
tags: Current sensing, current measurment, hall sensors, shunt
---


1. Introduction
Purpose of the Project: Briefly explain what the electronic device is and why you chose to design it.
Overview: Provide an overview of what the post will cover, including the design goals, challenges, and the final outcome.
Example: In this post, we’ll walk through the design and development of a custom portable power bank, covering everything from initial concept to the final prototype.
2. Project Concept and Requirements
Problem Statement: Define the problem that your device aims to solve or the need it fulfills.
Target Audience: Identify who the device is for and any specific needs they might have.
Design Objectives: List the key objectives, such as size, power capacity, efficiency, portability, or cost.
Example: The goal is to design a compact, lightweight power bank capable of charging smartphones and tablets with a capacity of at least 10,000mAh.
3. Research and Planning
Market Research: Discuss any existing devices on the market and how your design will differ or improve upon them.
Component Selection: Detail the research process for selecting components, such as batteries, charging circuits, voltage regulators, and connectors.
Design Tools: Mention the software and tools used for design, simulation, and PCB layout (e.g., KiCad, Eagle, LTSpice).
Example: We compared various Li-ion batteries based on capacity, weight, and cost. After research, we selected a 10,000mAh Li-ion battery due to its balance of energy density and portability.
4. Schematic Design
Circuit Design: Present the schematic of the device, explaining how each part of the circuit works.
Key Components and Their Roles: Describe the role of major components (e.g., microcontroller, power management IC, protection circuits).
Simulation (Optional): If applicable, include simulation results to demonstrate the circuit’s behavior under different conditions.
Example: The schematic includes a TP4056 charging IC for safe battery charging, and a DC-DC boost converter to step up the voltage to 5V for USB output.
5. PCB Layout
PCB Design: Show the PCB layout and discuss the considerations for component placement, trace routing, and thermal management.
Manufacturing Constraints: Mention any design decisions influenced by the manufacturing process, such as trace width, via size, or board layer count.
Example: The PCB layout was designed to minimize the footprint while ensuring good thermal management for the power components.
6. Prototype Development
Assembly: Describe the process of assembling the prototype, including soldering components and any challenges faced.
Testing and Debugging: Outline the testing process, highlighting how you verified the functionality of the device and any issues encountered.
Example: After assembling the prototype, we tested it with various devices to ensure stable output voltage and current. Some issues with heat dissipation were addressed by adding heatsinks.
7. Software and Firmware (if applicable)
Firmware Development: Discuss any firmware or software developed for the device, such as a microcontroller program to manage charging/discharging.
User Interface: If the device includes a user interface (e.g., LED indicators, display), explain its design and functionality.
Example: We developed firmware for an ATtiny85 microcontroller to monitor battery voltage and control the charging process.
8. Enclosure Design
Mechanical Design: Describe the process of designing the enclosure, including material selection and methods used (e.g., 3D printing, CNC machining).
Aesthetics and Ergonomics: Discuss the design considerations for the look and feel of the device, such as portability, durability, and user comfort.
Example: The enclosure was 3D-printed using ABS plastic, chosen for its durability and heat resistance. The design was kept sleek and compact to enhance portability.
9. Final Testing and Validation
Functional Testing: Summarize the results of the final testing phase, including any real-world usage scenarios.
Performance Metrics: Provide data on key performance metrics, such as battery life, charging time, efficiency, and thermal performance.
Example: The final prototype successfully charged a smartphone from 0% to 100% three times on a single charge, with a measured efficiency of 85%.
10. Challenges and Lessons Learned
Challenges Faced: Reflect on the challenges encountered during the project, such as technical issues, design revisions, or unforeseen difficulties.
Lessons Learned: Share insights gained from the project, including what worked well and what could be improved in future iterations.
Example: One of the biggest challenges was managing heat dissipation in a compact design. In future versions, I would explore using a metal enclosure to improve heat management.
11. Conclusion and Future Work
Summary: Recap the project, highlighting the key takeaways and the overall success of the design.
Future Improvements: Suggest possible improvements or additional features that could be added in future versions of the device.
Example: Overall, the custom power bank met the design objectives, but in future iterations, I would focus on reducing the overall size and improving charging speed.
12. Resources and References
Component Datasheets: Provide links to the datasheets of key components used in the design.
Tools and Software: Mention the tools and software that were particularly helpful during the design process.
Further Reading: Suggest books, articles, or videos for readers who want to learn more about the topics covered.
Example: Datasheets for the TP4056 charging IC and the chosen Li-ion battery can be found here.

Electronic load: https://github.com/bertrik/ElectronicLoad
13. Call to Action
Engagement: Encourage readers to leave comments, ask questions, or share their own projects related to the topic.
Example: Have you designed a custom electronic device? Share your experiences in the comments below!
14. Tags and Categories
Tags: Use relevant tags like electronics, DIY electronics, PCB design, prototyping, etc.
Categories: Place the post in a category such as Electronics Projects or Design Guides.
15. Comments Section
Allow readers to leave comments and engage with the content, asking questions or offering suggestions