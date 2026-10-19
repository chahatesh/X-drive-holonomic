# Holonomic Drivetrain

A simple, affordable, and easy-to-build 4-wheel holonomic drivetrain using TT motors and mecanum wheels.

Unlike traditional drivetrains, a holonomic drivetrain can move in any direction without turning, making it great for robotics projects.

## Features

- Forward and backward movement
- Sideways strafing
- Diagonal movement
- Rotation in place
- Independent control of all four wheels
- Simple, 3D-printable design

## Chassis Design

The chassis is designed to hold four TT motors and mecanum wheels in a compact configuration.

![Holonomic Drivetrain Chassis](images/Screenshot%202026-10-18%20134421.png)

## Required Components

| Component | Quantity |
|---|---|
| TT DC Motors | 4 |
| Mecanum Wheels (2 left, 2 right) | 4 |
| 4-Channel DC Motor Driver | 1 |
| Microcontroller (Arduino, ESP32, etc.) | 1 |
| Battery / Power Supply | 1 |
| Jumper Wires | As needed |
| 3D-Printed Chassis Parts | 1 Set |

**Note:** The motor driver must support four independently controlled DC motors.

## 3D Printing

All custom chassis components are designed to be 3D printed.

### Print Profile

The image below shows the print layout for the chassis components.

![3D Printing Profile](images/Screenshot%202026-10-18%20093518.png)

Print the required parts and assemble them using suitable fasteners.

## Assembly Instructions

1. 3D print the chassis components.
2. Attach the four TT motors to the chassis.
3. Install the mecanum wheels in the correct X-pattern arrangement.
4. Connect each motor to a separate motor driver channel.
5. Connect the motor driver to your microcontroller.
6. Connect a compatible power supply.
7. Upload your control code and test the motor directions.

## How It Works

A holonomic drivetrain uses specially designed wheels with angled rollers.

By independently changing each wheel's speed and direction, the robot can move forward, backward, sideways, diagonally, and rotate in place.

This makes the drivetrain useful for robots that need precise movement in tight spaces.

## Applications

- Robotics competitions
- Autonomous mobile robots
- Educational robotics
- Arduino and ESP32 projects
- Custom robotics platforms

## Project Goal

This project aims to make holonomic robotics affordable, accessible, and easy to build using common electronic components and 3D-printed parts.
