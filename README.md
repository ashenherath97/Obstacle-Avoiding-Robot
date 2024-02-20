# Obstacle Avoiding Robot

This Arduino project implements an Obstacle Avoiding Robot using ultrasonic sensors and servo motors.

## Hardware Components

- Arduino Board
- Ultrasonic Sensor (e.g., HC-SR04)
- Servo Motor
- Motor Driver (L298N)
- Chassis with Motors
- Power Supply (Battery or external power source)

## Wiring

Make sure to connect the components correctly:

- Ultrasonic sensor to digital pins 3 (Trigger) and 2 (Echo)
- Servo motor to pin 6
- Motors and motor driver connections:
  - Right Motor: Pins 11 (Speed), 12 (Forward), 13 (Backward)
  - Left Motor: Pins 5 (Speed), 4 (Forward), 8 (Backward)

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/ashenherath97/obstacle-avoiding-robot.git

