# Dual Power Supply Board

Compact ±12 V dual linear regulated power supply using LM317 and LM337 regulators.  
Designed for analog circuits, op-amp testing, and audio applications.

## Features
- 230 VAC input via Hammond 162J24 (12-0-12 V @ 1.5 A)
- Full-bridge rectifier (KBPC6)
- 22 000 µF filtering capacitors
- Adjustable ±1.25 V → ±12 V outputs
- Overcurrent & reverse-polarity protection

## Components
- **TR1:** Hammond 162J24 Transformer  
- **D1:** KBPC6 Bridge Rectifier  
- **U1 / U2:** LM317T, LM337T Regulators  
- **C1–C10:** Filtering and decoupling capacitors  
- **RV1 / RV2:** Adjustment potentiometers  
- **D2–D7:** Protection diodes  
- **J2:** Phoenix 3-pin Output Terminal

## Output Range
| Rail | Voltage | Current |
|------|----------|----------|
| V+   | +1.25 → +12 V | up to 1.5 A |
| V–   | –1.25 → –12 V | up to 1.5 A |

## Applications
- Audio preamp and op-amp circuits  
- Dual-supply analog prototypes  
- Lab power supply for small projects
