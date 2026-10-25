
Supernova Flight Computer

UHCL Rocket Club, Dec 2025 – Jun 2026 Avionics & PCB design: Jacob Flores (co-designer)

The flight computer for the club's Supernova rocket. It reads its sensors to track the rocket's motion, altitude, heading, and GPS position throughout the flight.

Assembled board 3D render

Hardware
Item	Details
MCU	Raspberry Pi RP2350
Sensors	6 on SPI: IMUs, barometers, magnetometer
Positioning	GNSS module
PCB	4 layers, designed in Altium Designer
Design work
Co-designed the schematic and the 4-layer PCB layout
Rev 2: found signal-integrity problems on the SPI sensor lines in Rev 1, then re-routed and improved the layout to fix them
Bring-up: diagnosed and repaired hardware faults, restoring the clock and firmware programming
What came next

Supernova's design led into Magnetar, the club's current flight computer: a modular stack of 95 mm boards (compute, power/pyro, and radio) that adds a 2-meter band (146 MHz) telemetry link built around a TI CC1200.

Files
schematics/: schematic PDFs (Rev 1 and Rev 2)
images/: renders and photos
<img width="3024" height="4032" alt="IMG_2555" src="https://github.com/user-attachments/assets/004157f2-e1bd-4f54-911c-865c18f83a37" />
