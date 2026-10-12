# Water Treatment Plant Automation (Siemens S7-1200)

Full automation of a water treatment plant built from scratch in
TIA Portal using SCL, with a KTP700 HMI.

## Features
- Custom PID with anti-windup (clamping) and bumpless transfer
- Pump sequencing with run-hour equalization
- Fault detection logic
- Structured alarm system on the HMI

## Tools
Siemens TIA Portal · S7-1200 · SCL · PID Control · KTP700 HMI

## Repository structure
- `scl/`: SCL source files
- `images/`: HMI screenshots and trend captures
- `docs/`: process diagram and logic diagrams

## Key lesson
Siemens big-endian byte ordering places alarm trigger bits starting
at bit 8 of %MW0. Easy to miss, and costs hours of debugging.

## Author
Bashar Bashery: Control Systems Engineering Student
LinkedIn: www.linkedin.com/in/bashar-bashary-4b5079418

