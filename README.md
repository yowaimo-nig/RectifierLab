# Rectifier Lab

Interactive single-page simulator of diode and thyristor-controlled bridge rectifiers, single-phase and three-phase, with a live circuit diagram and real-time voltage and current waveforms across any component you click.

## Features

- Single-phase and three-phase supply
- Diode bridge or thyristor-controlled bridge with adjustable firing angle α
- R–L load with adjustable R and L
- Circuit diagram on the left, with conducting devices highlighted
- Waveforms on the right: supply, load output (with average Vdc) and a probe plot for any component you select
- Readouts for measured Vdc, ideal Vdc and measured Idc

## Run it

No build step and no dependencies. Open `index.html` in a browser.

## Model

Time-domain simulation with ideal switches, an R–L load and no back-EMF. Supply is 325 V peak per phase at 50 Hz.
