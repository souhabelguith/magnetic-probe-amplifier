# Magnetic Probe Amplifier — INA849

HiWi project: signal amplifier PCB for magnetic probe coil measurements.

[Live page](https://souhabelguith.github.io/magnetic-probe-amplifier/)

## Project sources

- [TI INA849 datasheet — SBOS945B, Revision B](https://www.ti.com/lit/ds/symlink/ina849.pdf)
- [TI INA849 product page](https://www.ti.com/product/INA849)

## Typical device bandwidth

| Gain (V/V) | −3 dB bandwidth |
| --- | --- |
| 1 | 28 MHz |
| 10 | 13 MHz |
| 100 | 8 MHz |
| 1000 | 1.25 MHz |

Datasheet §7.5, p. 6: 25°C, ±15 V, 10 kΩ load to ground, REF=0 V, input common-mode=0 V. These are device values, not measured PCB specifications.

G = 1 + 6 kΩ/RG. The INA849 uses current feedback; a constant gain–bandwidth approximation is unsuitable. No 100 MHz board bandwidth is claimed.

## Board documentation

Actual gain resistor, supply configuration, schematic, layout, photographs, and measured amplitude/phase response remain to be supplied.

GitHub Pages serves index.html from main at the repository root.
