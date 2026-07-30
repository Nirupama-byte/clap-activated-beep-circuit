# Clap-Activated Beep Circuit

A clap-activated alert circuit designed using analog electronics and dual 555 timer ICs.

## Overview

This project detects two clap sounds occurring within a 3-second interval and activates a buzzer to generate a beep. The design demonstrates practical applications of analog signal conditioning, timing circuits, and PCB design.

Developed as a 4th Semester Electronic Circuits and Devices project.

---

## Features

- Electret microphone sound detection
- Audio signal amplification
- Frequency filtering
- Dual 555 Timer IC design
- 3-second clap detection window
- Beep output after successful double clap
- Custom PCB designed in EasyEDA

---

## Working Principle

1. The electret microphone captures the clap sound.
2. The signal is amplified and filtered.
3. The first 555 timer starts a 3-second timing window.
4. If a second clap is detected within this period:
   - Logic circuitry activates.
   - The second 555 timer generates an audio tone.
5. If no second clap occurs before timeout, the system resets.

---

## Hardware Used

- Electret Microphone
- NE555 Timer IC ×2
- LM358 (if used)
- BC547 Transistors
- Resistors
- Capacitors
- Diodes
- Piezo Buzzer
- LEDs
- 9V Power Supply

---

## Software

- EasyEDA
- Breadboard Prototype
- PCB Fabrication

---

## Repository Structure

Documentation/
Schematics/
PCB/
Simulation/
BOM/
Media/

---

## Results

✔ Successfully detects two claps within 3 seconds

✔ Ignores single clap events

✔ Generates audible beep output

✔ Successfully implemented on custom PCB

---

## Future Improvements

- Adjustable clap sensitivity
- Digital signal processing using a microcontroller
- Relay output for appliance control
- Battery-powered portable version

---

## Authors

- Theekshana Pradeep
- Nirupama Priyashan
