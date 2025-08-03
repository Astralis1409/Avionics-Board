---
Title: "VikramSat Avionics Board"
Author: "@Jaydev-1510"
Description: "OBC/C&DH Board for VikramSat by Astralis"
Created On: "3/08/2025"
---

# August 3: Ready for [grounded](https://grounded.hackclub.com)!

## Day - 01
This is the first day of the project. I will be working on the Avionics Board for VikramSat. The board will be responsible for handling the communication between the VikramSat and the ground station, and all the necessary data processing.

> I am excited to start working on this project. I will be documenting my progress here. 

I have finally choosen [RPi RP2350](https://raspberrypi.com/products/RP2350) after terrible research. It has got  dual Arm Cortex-M33 core @ 150MHz and dual Hazard3 RISC-V cores. I chose ICM-20948 because of its high accuracy and low power consumption. I feel BMP390 is a good choice for pressure sensor. Here's the parts I have chosen:

|Mention| Name | Commodity | Notes |
|:----: |:----:|:---:      |:----: |
|[![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)](https://raspberrypi.com)| RP2350 | MCU | 2(Cortex-M33+RISC-V) |
|[![Bosch](https://img.shields.io/badge/-Bosch-EA0016?style=for-the-badge&logo=Bosch)](https://bosch.com)| BMP390|Pressure sensor| - |
|[![TDK Invensense](https://img.shields.io/badge/-TDK-0046ad?style=for-the-badge)](https://invensense.tdk.com)|ICM-20948 | IMU | 9-axis IMU |

I have a prepared a block diagram. Check it out - 

<h1 align='center'>
  <img alt='Block diagram' heignt='auto' width='80%' src='images/Avionics-block-diagram.svg' />
</h1>

This the schematic I've prepared for today- 

<h1 align='center'>
  <img alt='Day-1 schematic' heignt='auto' width='100%' src='images/day-1-schematic.svg' />
</h1>

### Tasks completed today:

- [x] Chosen the MCU and other components for the Avionics Board.
- [x] Started designing the schematic.
- [x] Prepared a block diagram of the Avionics board for better idea.

### Total time spent today: 2 hours