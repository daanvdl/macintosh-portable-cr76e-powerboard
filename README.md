# Macintosh Portable M5136Z (CR-76E) Adapter PCB

## Overview
This project provides a drop-in replacement PCB for the **Sony Macintosh Portable M5136Z (CR-76E)** power board.
It is intended as a 1-to-1 replacement for the original PCB, allowing reliable restoration of Macintosh Portable systems where the original power board has become unreliable or irreparably damaged.

![Board](Images/board.png)
---

## Reason for This Project
Due to the use of poor quality end 80's/ early 90's electrolytic capacitors, many original Macintosh Portable power PCBs have suffered fromm severe electrolyte leakage, electrical instability or structural damage to the point where repair is no longer safe or reliable.
In many cases, recapping alone is not sufficient, and replacing the PCB is the only sensible long-term solution.
This adapter PCB was designed to address exactly that problem.

---

## Board
- Fully drop-in replacement. No system modifications required
- 1-to-1 replica of the original Sony CR-76E PCB
- Identical connectors, layout, and functionality
- Jumper wires have been replaced by PCB traces on the top layer

Electrically and functionally, this board behaves the same as the original.

---

## PCB Specifications
- **PCB thickness:** 1.6 mm
- **Surface finish:** HASL (sufficient for this design)
- **Layers:** 2-layer PCB

---

## Bill of Materials (BOM)

This Bill of Materials (BOM) is provided for reference purposes only. Component values, part numbers, and descriptions are based on reverse engineering and visual inspection and may be incomplete or inaccurate. No guarantee is given regarding correctness, suitability, or fitness for any particular application. Use this information at your own risk. Always verify components against the original hardware and schematics before ordering or assembling parts.

| Name  | Value                  | Comment                                                   |
| ----- | ---------------------- | --------------------------------------------------------- |
| C102  | XE223 0.022uF 250V X2  |                                                           |
| C103  | N/A                    | NOT POPULATED                                             |
| C104  | 2200 pF (KC222M)       |                                                           |
| C105  | 2200 pF (KC222M)       |                                                           |
| C106  | 2200 pF (KC222M)       |                                                           |
| C107  | 2200 pF (KC222M)       |                                                           |
| C108  | N/A                    | NOT POPULATED                                             |
| C109  | 47uF/400V              | Panasonic EEU-ED2G470                                     |
| C110  | 103K630                |                                                           |
| C111  | 2200 pF (KC222M)       |                                                           |
| C201  | 2200uF/16V             | Panasonic EEU-FM1C222B                                    |
| C203  | 330uF/16V              | Panasonic EEU-FM1C331B                                    |
| C204  | N/A                    | NOT POPULATED                                             |
| C205  | N/A                    | NOT POPULATED                                             |
| C206  | 100uF/25V              | Panasonic EEU-FR1E101B                                    |
| CN101 | CN201                  | SIDE BOARD                                                |
| D101  | GI DF05                | Bridge Rectifier. Can be replaced with DF06 and DF10      |
| D102  | likely UF4007 or FR107 | Snubber circuit                                           |
| D103  | BZX55-C7V5             | 7.53                                                      |
| D201  | FMB29L                 | MBR1060CT / MBR10100CT                                    |
| D202  | 1N5817/1N5819          | 1N5817                                                    |
| D203  | N/A                    | NOT POPULATED                                             |
| L101  | 4S-333 V99             |                                                           |
| L201  | 100M Inductor          | Sony 408-933-11 / 100M Inductor                           |
| PS101 | ICP-N10                |                                                           |
| Q101  | IRFIBC20               |                                                           |
| R101  | 1.8M 1/2W Metal        |                                                           |
| R102  | 3.3 Ohm 2W AGH         |                                                           |
| R103  | 330K Ohm 1/8W carbon   |                                                           |
| R104  | 330K Ohm 1/8W carbon   |                                                           |
| R105  | 27K ohm 1/8W carbon    |                                                           |
| R106  | 47K Ohm 1/2W (beige)   |                                                           |
| R107  | 100Ohm 1/4W carbon     |                                                           |
| R108  | 1.2Ohm 1/4W carbon     |                                                           |
| R109  | N/A                    | NOT POPULATED                                             |
| R201  | 0.1Ohm 1/4W (beige)    |                                                           |
| R202  | 220Ohm 1/2W (beige)    |                                                           |
| R203  | N/A                    | NOT POPULATED                                             |
| T101  | Sony A-4935-112-A      | D9D01 SONY                                                |

---

## References

1. **THEtechknight** – *Macintosh Portable AC Adapter Restoration*  
   YouTube video covering analysis and restoration of the Macintosh Portable AC adapter / power board.  
   The video clearly demonstrates the type of damage caused by leaking electrolytic capacitors.  
   Note: The damage may be significantly worse than shown in this video.  
   https://www.youtube.com/watch?v=47v9GxB199Y&t=660s

2. **MacDat.net – Macintosh Portable AC Power Board Capacitor Reference**  
   Capacitor reference overview for the Macintosh Portable AC power board, provided for cross-checking component values and placement.  
   See also the **Bill of Materials (BOM)** section.  
   https://macdat.net/repair/cap_reference/apple/powerbook/portable_ac.html

3. **cr76u-hybrid** (mounted on the sideboard of the main PCB)
   CR-76D Shin EI IC Recreation for the Sony CR-76U Power Supply used in the Macintosh Portable.
   https://github.com/thetechknight/cr76u-hybrid/tree/main

---

## Disclaimer
This project is intended for retro-computing and restoration purposes nly. Use at your own risk. Always verify output voltages before connecting valuable hardware.

---

*With this project, I hope to help preserve the Macintosh Portable by providing a reliable and reproducible replacement for one of its most failure-prone components.*
