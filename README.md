# Multi-Functional Arduino Robot

This project implements a multi-functional robot using the Arduino platform. The robot supports three control modes: obstacle avoidance, Bluetooth control, and voice control. It utilizes an ultrasonic sensor, a Bluetooth module, and an L293D motor driver shield to navigate and respond to user commands.

## Features

- **Obstacle Avoidance**: The robot moves autonomously, detecting and avoiding obstacles using an ultrasonic sensor.
- **Bluetooth Control**: Users can control the robot remotely through a smartphone app via Bluetooth.
- **Voice Control**: The robot responds to specific voice commands for directional movement.

## Components Used

- Arduino Uno
- AFMotor Shield (L293D)
- HC-05 Bluetooth Module
- Ultrasonic Sensor (HC-SR04)
- Servo Motor
- DC Motors and Wheels
- Power Supply

## How It Works

1. **Obstacle Avoidance Mode**: The ultrasonic sensor detects obstacles, and the robot changes direction accordingly.
2. **Bluetooth Control Mode**: The robot can be manually controlled via a mobile app using Bluetooth.
3. **Voice Control Mode**: The robot listens to voice commands from the mobile app and moves accordingly.

## Getting Started

1. **Hardware Setup**: Connect all components as per the circuit diagram.
2. **Code Upload**: Flash the `sketch.ino` file to the Arduino board.
3. **Bluetooth Pairing**: Pair the HC-05 module with your mobile device.
4. **Testing**: Power on the robot and switch between different control modes.


