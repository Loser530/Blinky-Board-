# Blinky-Board-
This repository contains the PCB design files for a 10-Channel Sequential LED Flasher, designed in EasyEDA. The board is engineered to trigger ten LEDs in a precise, repeating sequence. This project serves as a robust solution for custom visual displays, signal indicators, and decorative lighting effects.

🛠 Design Process
The development of this PCB followed a structured engineering workflow:

Logic & Schematic Design: I designed the circuit to handle a 10-stage output logic. I focused on ensuring the clock signal is stable to provide a smooth transition between each light in the sequence.

Component Selection: I chose specific resistors and transistors to ensure that each LED receives uniform current, preventing brightness fluctuations across the 10 channels.

PCB Routing: * Designed a symmetrical layout for the LED array to ensure a clean aesthetic.

Implemented optimized trace routing to minimize signal cross-talk between the sequential outputs.

Added a dedicated power rail for stable voltage distribution across the entire board.

Testing: Verified the design using EasyEDA’s built-in simulation and Design Rule Check (DRC) to ensure the board is 100% ready for manufacturing.

📂 File Structure
PCB layout:<img width="587" height="435" alt="Screenshot 2026-04-18 172025" src="https://github.com/user-attachments/assets/67e43e46-7965-4012-9472-d0e61549be44" />


 <img width="732" height="661" alt="Screenshot 2026-04-18 172233" src="https://github.com/user-attachments/assets/d747b63d-c514-4d89-a71d-a1cf9d310a57" />



🚀 Purpose
The primary purpose of this design is to provide an automated sequential signaling system. It can be integrated into larger electronics projects where a visual "chase" effect or a multi-stage status indicator is required.
