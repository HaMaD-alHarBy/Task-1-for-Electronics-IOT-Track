# Task-1-for-Electronics-IOT-Track
 
# Arduino LED Control Project

## Project Overview

This project demonstrates how to control multiple LEDs using an Arduino Uno and a pushbutton. When the button is pressed, three LEDs (green, yellow, and orange) light up simultaneously, and they turn off when the button is released.


## Components List

![Screenshot 2025-07-09 183347](https://github.com/user-attachments/assets/5edef725-ea6e-4c89-b303-a02962b67122)


## Circuit Diagram

### The circuit consists of:

- Arduino Uno as the main controller

- Pushbutton connected to pin 2 with a 1 kΩ pull-down resistor

- Three LEDs (pins 11, 12, 13) each with 220 Ω current-limiting resistors

- Common ground connection


![Screenshot 2025-07-09 183250](https://github.com/user-attachments/assets/979de07c-3726-43f7-bc59-6d985ae0b55b)



## Code Explanation

![Screenshot 2025-07-09 194348](https://github.com/user-attachments/assets/d1dab91e-c5c1-49df-944d-6e39d0fac1fc)


## How to Use

- Connect the circuit as shown in the diagram

- Upload the provided code to your Arduino Uno

- Press the button to light up all three LEDs

- Release the button to turn them off


## Safety Notes

- Always use current-limiting resistors for LEDs (220Ω recommended)

- Double-check connections before powering the circuit

- Ensure proper polarity for all components (LEDs, etc.)
