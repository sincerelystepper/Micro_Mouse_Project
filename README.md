# Micro_Mouse_Project
This is the micromouse project that aims to solve a maze. It consists of four modules: a processor (stm32l), a power module, a sensor module. These all interface to aid a functional micromouse. Hence this repo exhibits the interconnection between these modules. This project involves building the power adn sensing sub-modules the simplified micro-mouse.

Project Overview
The project entails designing and manufacturing two key modules: the Sensor Module and the Power Module. Each module plays a crucial role in the functionality of the micro-mouse:

Sensor Module: Responsible for detecting and sensing objects within the maze.
Power Module: Responsible for powering the entire system, including running the motors and charging a battery.

Modules Overview
1. Motherboard
The motherboard serves as the baseboard that all other modules will slot onto. It's responsible for connecting all the PCBs together.

2. Processor
The processor board includes the STM32L476 microcontroller. It provides 78 output pins for use, with most connections already dictated by required interconnections.

3. Sensor Module
Responsibility: Detecting and sensing objects.
Requirements:
• Detect whether there is an obstacle in front of the robot and on the sides too.
• Have switching means to save power when not in operation.
• Design for reliability such that system can be proven to work.
• Consider how much power and current the sensing board is drawing such that battery is not drained before the maze is solved.
• Write some code interfacing the sensor with the rest of the system and prove it senses the
wall. The processor board has 3 LEDs, so 1 used to indicate a wall is sensed on the right, 1 to indicate that there is
a wall on the left and 1 to indicate a wall in front of the robot. If no wall is sensed, then no
LEDs will be on
•Must fit onto the pin headers on the motherboard.
•Appropriate size for the robot.
Design and Manufacturing: The task here involves designing and manufacturing this module to meet the specified requirements.

4. Power Module
Responsibility: Powering the entire system, including running motors and charging a battery.
Requirements:
• Operate 2 motors with the pins available. As well as to control
2x motors which could each draw 200mA at the highest voltage of a 1S1P battery
• Needs to provide an analog connection that provides information on the battery's voltage for
the processor to sense battery state of charge (SoC).
• Needs to charge the battery from the 5V input pin.
• Needs an ON/OFF switch. OFF state: battery draw <500uA. ON state: your robot peak
current.
•Must fit onto the pin headers on the motherboard.
•Appropriate size for the robot.
Design and Manufacturing: The task here is to design and manufacture this module to meet the specified requirements.

License
This project is licensed under the MIT License, which permits both commercial and non-commercial use.

Contributors
Kopano Maketekete:GitHub Profile-->sincerelystepper
Chukwudi Iloanya: GitHub Profile--> ChukwudiIloanya

Feel free to reach out to any one of us for any questions or clarifications regarding the project.
