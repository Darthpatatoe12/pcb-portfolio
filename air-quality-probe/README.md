Portable Air Quality System — Probe PCB

Senior design project (UHCL Computer Engineering), Jan 2026 – present Team: Jacob Flores (PCB design & assembly), Piotr Smieja, John Griffin

A drone-mountable air quality probe and ground station that measures the main EPA pollutants in real time, computes the Air Quality Index (AQI), and sends the data to the ground over a long-range radio link.

Assembled board 3D render

What it does
Measures O₃, CO, SO₂, NO₂, and PM2.5/PM10
Computes the EPA AQI on the board
Sends live telemetry to a ground station over a TI CC1120 sub-GHz radio
Logs data to an SD card
Runs on an internal battery or on power from the host drone
Hardware
Item	Part
MCU	Raspberry Pi RP2350A
Radio	TI CC1120 sub-GHz transceiver
Particulate matter	Sensirion SPS30
Ozone	Winsen MQ131
Carbon monoxide	SGX PS1-CO-1000
Nitrogen dioxide	SGX-4NO2
Sulfur dioxide	SPEC 110-601

PCB: 4 layers (signal / plane / plane / signal), 90.3 × 75.6 mm, all SMT parts on the top side. Designed in Altium Designer.

My role
Designed the schematic and the 4-layer layout in Altium, laying out each circuit to its component datasheet
Made custom footprints for the sensors
Designed and tested the electrochemical sensor driver circuits
Hand-soldered the SMT parts and brought up the board
Files
schematics/: schematic PDF
images/: renders and photos
<!-- Optional: add a "Results" section with test data or a short video once the system is flying. -->

<img width="2160" height="2880" alt="empty" src="https://github.com/user-attachments/assets/6c16cc9b-0d1f-4f67-9ee8-2d44ef80dae5" />
