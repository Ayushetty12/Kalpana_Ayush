# Kalpana_Ayush
## Readme
**Project 1:** Controlling LED Brightness with a Button (3 Levels)
**Project 2:** 4-Bit Up Counter Using LEDs
**Project 3:** 7-Segment Display Counter (1 to 1000 and back to 1)
## Project 1 - Controlling LED Brightness with a Button (3 Levels)
**Description:**  
This project allows you to control the brightness of an LED using a single button. Each time the button is pressed, the LED cycles through three brightness levels: low, medium, and high.
**Components Used:**
- Arduino Uno (or compatible board)
- 1 x LED
- 1 x 220Ω resistor (for LED)
- 1 x Push button
- 1 x 10kΩ resistor (for button pull-down, if not using INPUT_PULLUP)
- Jumper wires
- Breadboard
**Tinkercad Simulation:**  
https://www.tinkercad.com/things/2gL3nnP2zPJ-brightness-control
## Project 2 - 4-Bit Up Counter Using LEDs

**Description:**  
This project demonstrates a simple 4-bit binary up counter using four LEDs. The LEDs visually represent the binary value of a counter incrementing from 0 to 15.

**Components Used:**
- Arduino Uno (or compatible board)
- 4 x LEDs
- 4 x 220Ω resistors
- Jumper wires
- Breadboard

**How it Works:**  
- Four digital pins are used to drive four LEDs.
- The counter variable increments from 0 to 15.
- The state of each LED represents one bit of the counter (least significant to most significant).
- The LEDs light up in a pattern corresponding to the binary representation of the counter value.
**Tinkercad Simulation:**  
https://www.tinkercad.com/things/aISYhfAN3lR-counter
## Project 3 - 7-Segment Display Counter (1 to 1000 and back to 1)

**Description:**  
This project uses a 3-digit 7-segment display to count from 1 to 1000 and then back to 1 in a loop. Each number is displayed in real-time on the display.

**Components Used:**
- Arduino Uno (or compatible board)
- 1 x 3-digit 7-segment display (common cathode)
- 7 x 220Ω resistors (for segments)
- 3 x 220Ω resistors (for digit control)
- Jumper wires
- Breadboard

**How it Works:**  
- Seven segment pins are connected to Arduino digital outputs.
- Digit select pins are used to multiplex the display for each digit.
- The code splits the number into hundreds, tens, and units, displaying each digit in quick succession to create the illusion of a steady display (multiplexing).
- The counter increases from 1 to 1000, then decreases back to 1, repeating indefinitely.
**Tinkercad Simulation:**  
https://www.tinkercad.com/things/fk4llu6eg1K-7-segment-
