# Mini Oscilloscope — PIC16F877A & GLCD

An educational waveform visualization project using a PIC16F877A microcontroller and a 128×64 graphical LCD, simulated in Proteus.

## Overview

The microcontroller samples an analog signal through its ADC, maps the readings to display coordinates, and draws connected points on the GLCD.

## Components and Tools

- PIC16F877A microcontroller
- AMPIRE 128×64 graphical LCD
- Crystal oscillator and contrast potentiometer
- Proteus simulation
- mikroC PRO for PIC

## Project Files

The `project.zip` archive contains:

- `New Project.pdsprj` — Proteus schematic
- `g2/MyProject.c` — firmware source
- `g2/MyProject.hex` — compiled firmware
- Supporting mikroC project and build files

## Running the Simulation

1. Extract `project.zip`.
2. Open `New Project.pdsprj` in Proteus.
3. Open the PIC16F877A component properties.
4. Set **Program File** to the extracted `g2/MyProject.hex`.
5. Set **Processor Clock Frequency** to **8 MHz**.
6. Start the simulation.

## Author

Ali Mirzaabolhassani
