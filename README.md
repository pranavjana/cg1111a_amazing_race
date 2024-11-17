# mBot Maze Solver Project

## Overview

This project involves an mBot robot designed to autonomously navigate through a maze and complete several color-sensing challenges. The goal is to demonstrate engineering principles related to sensor integration, algorithmic decision-making, and control system design, which were learned during the course of the project.

The mBot is equipped with color detection sensors, line-following logic, and wall-following capabilities. Using RGB LEDs, an LDR sensor, and a PID control system, the robot effectively navigates the maze, detects key colored markers, and takes appropriate actions based on the environment.

## Features
- **Autonomous Maze Navigation**: The mBot traverses a maze, using ultrasonic and IR sensors for obstacle detection and wall following.
- **Color Detection Challenges**: The mBot detects various colors placed within the maze and performs specific actions accordingly.
- **PID-Controlled Wall Following**: Ensures smooth navigation by keeping a consistent distance from walls using a tuned PID algorithm.
- **Integrated LDR Color Sensing**: Uses RGB LEDs in combination with a Light Dependent Resistor (LDR) to classify colors accurately.

## Key Engineering Principles
1. **Control Systems**: PID control is implemented to keep the robot at an optimal distance from maze walls.
2. **Sensor Calibration**: RGB color values were calibrated to differentiate between multiple colors, addressing challenges such as ambient light interference.
3. **Algorithm Optimization**: Code logic was streamlined to improve efficiency and ensure fast, consistent performance in line detection and maze navigation.

## Getting Started
To run the mBot in your own environment, follow these steps:

1. **Hardware Setup**: Ensure the mBot is assembled properly with RGB LEDs, LDR sensors, and IR and ultrasonic sensors attached.
2. **Code**: Upload the provided source code to the mBot via the mBlock IDE.
3. **Calibration**: Before starting, calibrate the sensors for ambient light conditions and adjust PID parameters as needed.

## Dependencies
- **mBlock IDE**: To program and upload code to the mBot.
- **Arduino Libraries**: The project uses several libraries, including the mBot library for hardware interfacing and motor control.

## Running the Code
- Once the mBot is powered on and the code is uploaded, press the start button to begin the maze-solving routine.
- The mBot will autonomously navigate, detect colors, and make decisions based on its environment.


## Project Team
- **Roshan**: Report writing, LDR and IR circuitry, color sensing code implementation.
- **Pranav**: Report writing, robot movement code, LDR casing design, color sensing code implementation.
- **Wei Hao**: Report writing, LDR and IR circuitry, LDR casing design.
- **Asher**: Report writing, LDR and IR circuitry, IR sensing code implementation.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Inspired by "The A-maze-ing Race Project 2024."
- Thanks to all team members for their contributions and hard work throughout this project.

Feel free to clone, modify, and explore the code. Contributions are welcome to improve and build upon this project!
