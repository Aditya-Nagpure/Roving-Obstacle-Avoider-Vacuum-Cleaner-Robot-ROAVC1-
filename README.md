# Roving-Obstacle-Avoider-Vacuum-Cleaner-Robot-ROAVC1
The Roving-Obstacle-Avoider-Vacuum-Cleaner (ROAVC1) is an autonomous robot designed to clean floors efficiently while avoiding obstacles. The robot leverages sensor data to navigate through various environments, ensuring thorough cleaning without human intervention. This project combines elements of robotics, IoT, and intelligent systems to create a smart cleaning solution.

##Components
1. Microcontroller: Arduino Uno (or similar)
2. Sensors: Ultrasonic sensors for obstacle detection, IR sensors for edge detection
3. Motors: DC motors for movement
4. Vacuum Cleaner: A small motor-driven vacuum unit for cleaning
5. Battery: Rechargeable lithium-ion battery
6. chassis: Custom-designed chassis with space for mounting all component

##System Design on Tinkercad
   <img width="959" alt="image" src="https://github.com/user-attachments/assets/ff02170e-af34-4de9-ac8d-06613e8b5bce">

##How It Works
1. Initialization: The microcontroller initializes the sensors and motors upon startup.
2. Sensing: The ultrasonic sensors continuously monitor the surroundings for obstacles.
3. Decision Making: When an obstacle is detected, the robot calculates the best route to avoid it.
4. Movement: The robot adjusts its path and continues cleaning, ensuring it covers the entire area.
5. Vacuuming: The vacuum unit operates simultaneously, collecting dust and debris as the robot moves.
