# Macintosh Portable M5136Z (CR-76E) Adapter PCB

## Overview
This project provides a **drop-in replacement PCB** for the **Sony Macintosh Portable M5136Z (CR-76E)** power board (Sony design).
It is intended as a 1-to-1 replacement for the original PCB, allowing reliable restoration of Macintosh Portable systems where the original power board has become unreliable or irreparably damaged.

![Board](Images/board.png)
---

## Reason for This Project
Due to the use of **poor-quality electrolytic capacitors**, many original Macintosh Portable power PCBs have suffered from:
- severe electrolyte leakage,
- electrical instability,
- or structural damage to the point where repair is no longer safe or reliable.

In many cases, recapping alone is not sufficient, and replacing the PCB is the only sensible long-term solution.
This adapter PCB was designed to address exactly that problem.

---

## Board
- ✅ Fully drop-in replacement. No system modifications required
- ✅ 1-to-1 replica of the original Sony CR-76E PCB
- ✅ Identical connectors, layout, and functionality
- ✅ Jumper wires have been replaced by PCB traces on the top layer

Electrically and functionally, this board behaves the same as the original.

---

## Compatibility
- Macintosh Portable **M5136Z**
- Power board: **Sony CR-76E**

---

## PCB Specifications
- **PCB thickness:** 1.6 mm
- **Surface finish:** HASL (sufficient for this design)
- **Layers:** 2-layer PCB

---

## Bill of Materials (BOM)

This Bill of Materials (BOM) is provided for reference purposes only. Component values, part numbers, and descriptions are based on reverse engineering and visual inspection and may be incomplete or inaccurate. No guarantee is given regarding correctness, suitability, or fitness for any particular application. Use this information at your own risk. Always verify components against the original hardware and schematics before ordering or assembling parts.

| Name  | Value                 | Comment                                              |
| ----- | --------------------- | ---------------------------------------------------- |
| C102  | XE223 0.022uF 250V X2 |                                                      |
| C103  | N/A                   | NOT POPULATED                                        |
| C104  | 2200 pF (KC222M)      |                                                      |
| C105  | 2200 pF (KC222M)      |                                                      |
| C106  | 2200 pF (KC222M)      |                                                      |
| C107  | 2200 pF (KC222M)      |                                                      |
| C108  | N/A                   | NOT POPULATED                                        |
| C109  | 47uF/400V             |                                                      |
| C110  | 103K630               |                                                      |
| C111  | 2200 pF (KC222M)      |                                                      |
| C201  | 2200uF/16V            |                                                      |
| C203  | 330uF/16V             |                                                      |
| C204  | N/A                   | NOT POPULATED                                        |
| C205  | N/A                   | NOT POPULATED                                        |
| C206  | 100uF/25V             |                                                      |
| D101  | GI DF05               | Bridge Rectifier. Can be replaced with DF06 and DF10 |
| D102  | unreadable            |                                                      |
| D103  | unreadable            | zener?                                               |
| D201  | FMB29L                | MBR1060CT / MBR10100CT                               |
| D202  | 1N5817/1N5819         | 1N5817                                               |
| D203  | N/A                   | NOT POPULATED                                        |
| F101  | FUSE HOLDER           |                                                      |
| L101  | 4S-333 V99            |                                                      |
| L201  | 100M Inductor         | Sony 408-933-11 / 100M Inductor                      |
| PS101 | Nickel Oxide Varistor |                                                      |
| Q101  | N-MOSFET              | 600 V N-MOSFET: 7N60 / 9N60 / 11N60 / 13N60          |
| R101  | 1.8M Ohm 1/2W Metal   |                                                      |
| R102  | 3.3 Ohm 2W AGH        |                                                      |
| R103  | 330K Ohm 1/8W carbon  |                                                      |
| R104  | 330K Ohm 1/8W carbon  |                                                      |
| R105  | 27K ohm 1/8W carbon   |                                                      |
| R106  | 47K Ohm 1/2W          |                                                      |
| R107  | 100 Ohm 1/4W carbon   |                                                      |
| R108  | 1.2 Ohm 1/4W carbon   |                                                      |
| R109  | N/A                   | NOT POPULATED                                        |
| R201  | 0.1 Ohm 1/4W          |                                                      |
| R202  | 220 Ohm 1/2W          |                                                      |
| R203  | N/A                   | NOT POPULATED                                        |
| T101  | Sony A-4935-112-A     | D9D01 SONY TRANSFORMER                               |

---

## Disclaimer
This project is intended for retro-computing and restoration purposes nly. Use at your own risk. Always verify output voltages before connecting valuable hardware.

---

*With this project, I hope to help preserve the Macintosh Portable by providing a reliable and reproducible replacement for one of its most failure-prone components.*
