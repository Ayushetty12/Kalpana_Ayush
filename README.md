Task 3:
1. I2C Communication Protocol
What is I2C?
I2C (Inter-Integrated Circuit) is a two-wire, synchronous serial communication protocol used to connect multiple peripherals to microcontrollers.

Uses two lines: SDA (Serial Data) and SCL (Serial Clock).

One device acts as a controller (master), others as targets (slaves).

Each device has a unique address.

1. Counting 1–40 and Back Using a 7-Segment Display (Tinkercad)
Objective: Display numbers from 1 to 40 and then back to 1 on a 7-segment clock display using Arduino.

How It Works: The Arduino controls multiple 7-segment displays through multiplexing, lighting up the correct segments to show each number in sequence. The code increments the displayed number up to 40, then decrements back to 1, creating a continuous counting loop.

Skills Learned: Multiplexing displays, digital output control, number-to-segment mapping, and basic loop logic in Arduino programming.

https://www.tinkercad.com/things/c8oX68teLzy-7-seg-display

2. Servo Motor Sweep: 0 to X Degrees and Back (Tinkercad)
Objective: Move a servo motor smoothly from 0 degrees to a specified angle (X) and back to 0, repeating this cycle.

How It Works: The Arduino uses the Servo library to generate precise control signals. The servo’s signal wire is connected to a PWM-capable digital pin. The code gradually increases the servo angle from 0 to X, then reverses the motion, creating a smooth, continuous sweep.

Skills Learned: PWM signal generation, library usage (Servo.h), precise angular control, and hardware interfacing with actuators.

https://www.tinkercad.com/things/gCBLQmZcxvj-servo-pos-x

3. Stepper Motor Control: X Rotations, Direction, and Speed (Wokwi)
Objective: Rotate a stepper motor a user-defined number of turns, in a specified direction and at a set speed, using Arduino.

How It Works: The Arduino uses the Stepper library to send step pulses to the motor. The code sets the number of steps (for rotations), the speed (in RPM), and direction (by step count sign). The motor rotates the set amount, pauses, then can reverse or repeat based on the program logic.

Skills Learned: Stepper motor interfacing, step/direction control, speed adjustment, and using libraries (Stepper.h) for motion projects.
https://wokwi.com/projects/435881097054971905
