# Keyboards (WIP)

Mechanical Keyboard & Keypad Designs & my process iterating them

## Overview

Since June 2024, I have been designing and prototyping mechanical keypads in order to learn more about PCB Design, electronics, firmware, 3D Modeling, and design for manufacturing. Since then, I have gone through 3 main iterations, improving on price, footprint/profile, and usability. I hope to end up with a fully polished design that passes as an actual product available from a manufacturer. 

### Tools:
- 3D Modeling: [OnShape](https://www.onshape.com/en/)
  - Online
  - Free
  - Well documented
- PCB Design: [EasyEDA](https://easyeda.com/)
  - Free
  - Integraded with JLC PCB
- PCB Provider: [JLCPCB](https://jlcpcb.com/)
  - Extremely Cheap
  - Relatively Fast
  - Supports a wide range of devices for assembly
- Firmware: [QMK](https://qmk.fm/)
  - Open Source
  - Widely used & well documented

<br>

---

## Rev 4 (Current Version)

### Images

<img src="pad_rev3/Rev3_Top.jpg" alt="drawing" width="49%"><img src="pad_rev3/Rev3_Angle1.jpg" alt="drawing" width="49%"><br>
<img src="pad_rev3/Rev3_Angle2.jpg" alt="drawing" width="49%">

#### PCB Schematic

<img src="pad_rev3/pad1_rev3.png" alt="drawing" width="35%">

### Notes

---

## Rev 1

### Images

<img src="pad_rev1/Rev1_Top.jpg" alt="drawing" width="49%"><img src="pad_rev1/Rev1_Open1.jpg" alt="drawing" width="49%">

- [Microcontroller](https://www.sparkfun.com/products/12640): Ardino Pro Micro (ATMega32U4-MU)

### Notes

This iteration was mainly to get an understanding of the PCB design and order process through JLCPCB. 



The design features 12 keys, a rotary encoder, and an Arduino Pro Micro.

Programming was developed and flashed through the Arduino IDE.

#### Improvements needed:
SMT Microcontroller <br>
Improve asthetics with black board <br>
Streamline case design <br>

---

## Rev 2

### Images

<img src="pad_rev2/Rev2_Top.jpg" alt="drawing" width="49%"><img src="pad_rev2/pad1_rev2.png" alt="drawing" width="49%">

USB Port on Rev2 (Left) vs Rev1 (Right)

<img src="pad_rev2/Rev2_Back.jpg" alt="drawing" width="49%"><img src="pad_rev1/Rev1_Back.jpg" alt="drawing" width="49%">

- [Microcontroller](https://www.digikey.com/en/products/detail/microchip-technology/ATMEGA32U4-AU/1914602): ATMega32U4-AU

### Notes

#### Changes

---