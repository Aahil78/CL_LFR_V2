# Cyber Link LFR V2

This project is a Line Following Robot (LFR) designed to autonomously navigate along a designated track. It utilizes a PID (Proportional-Integral-Derivative) control algorithm, the brain of the operation, to ensure smooth and accurate line tracking.

# Function

Imagine a tiny robot, eyes fixed on a black line, gracefully gliding across a surface. That's the magic of this LFR! It uses a QTR8RC line sensor array, like a set of tiny eyes, to detect the track. The Arduino Nano microcontroller, the robot's command center, processes the sensor data and uses the PID algorithm to direct the TB6612FNG motor driver. This driver controls two N20 motors, the robot's powerful legs, connected to N20 tires for smooth movement. The MP1584 breakout board keeps everything powered up.

# Fwatures

Line Sensor: QTR8RC - The robot's "eyes" that detect the track.
Microcontroller: Arduino Nano - The robot's brain, processing sensor data and controlling the motors.
Motor Driver: TB6612FNG - The muscle that controls the motors' speed and direction.
Motors: N20 - The robot's powerful legs, driving it forward.
Tires: N20 - Providing traction for smooth movement.
Caster Ball: Ensuring stability and smooth turns.
Power Supply: MP1584 - The energy source that keeps the robot running.
Capacitor: 0.1uF - Smoothing out the power flow.
LED (Green): A tiny green light that signals the robot is alive and well.
Resistor: 220 ohm - Keeping the LED's light just right.
N20 Bracket: Holding the motors securely in place.
# Algorithim 

The heart of this project is the PID algorithm. Think of it as a sophisticated balancing act. The QTR8RC sensor array constantly feeds information to the Arduino Nano about the robot's position on the track. The PID algorithm uses this data to calculate the precise adjustments needed for the motors, ensuring the robot stays perfectly centered on the track, even when navigating curves or uneven surfaces.
- NOTE: The code is a Work in Progress (I have been busy in studies), I'll make a V3 and get back to the programming soon.
