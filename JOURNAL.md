### View latest KiCad files at [KiCanvas](https://kicanvas.org/?github=https://github.com/Jaydev-1510/Avionics-Board/tree/main/Hardware)

---

# Day-1 (17/07/2025)

This was the day I started this project. Feeling excited, I started with the block diagram. I was cofused thinking about the processor/OBC for the avionics board. At first, I thought of using some STM processor from the STM-F and STM-H series. At the same time I believed in the simplicity of using Raspberry Pi RP2040/2354. But they were not powerful for processing images and heandling telemetry at the same time. I liked the Raspberry Pi 5 module, but I could not use it as it was big. Then I got and idea of using Raspberry Pi CM5 a smaller version of Raspberry Pi 5. Finaly I chose Raspberry Pi CM5. I also explored various projects like the [PhoenixSat](), [ORCAsat](orcasat.ca) and the CubeSat of [Build a CubeSat](youtube.com/@buildacubesat). Here is the block diagram I prepared.

![Block Diagram]()

## Tasks completed today:

- Creation of repository and initial commits.
- Surfing and research on other projects.
- Creation of [**KiCad**](kicad.org) project.
- Chose [**Raspberry Pi CM5**](raspberrypi.com/products/compute-module-5/) as the C&DH module and OBC.

### Time spent todday ~1.5h

---

# Day-2 (18/07/2025)

So, it were the IMU and the pressure sensor which were not finalised. After asking [ChatGPT](chatgpt.com) multiple times I decided to choose the ICM-20948 as the IMU because it was perfect for my application. It has got great precision and temperature range. Also I decided the pressure sensor as the [Bosch BMP390](https://www.bosch-sensortec.com/products/environmental-sensors/pressure-sensors/bmp390/). I thought of starting with the schematics. So, I started with it. By the way you can view the schematics and the PCB files at [KiCanvas](https://kicanvas.org/?github=https://github.com/Jaydev-1510/Avionics-Board/tree/main/Hardware) without downloading them! I have started with the basic connections as per the component's datasheets. I have added the schematic picture for your reference.

![Schematic]()

## Tasks completed today:

- Started with the schematic.
- [**Invensense ICM-20948**](https://invensense.tdk.com/products/motion-tracking/9-axis/icm-20948/) is now the IMU and magnetometer.
- Also added [**Bosch BMP390**](https://www.bosch-sensortec.com/products/environmental-sensors/pressure-sensors/bmp390/) as the pressure sensor.

### Time spent todday ~2h

---

# Day-3 (20/07/2025)

The GPS of the cubesat will be attached to the avionics board only with the help of headers. After entering many prompts I am impressed by the [**NovAtel OEM-719**](https://novatel.com/products/receivers/gnss-gps-receiver-boards/oem719) and i think I will be able to use it if budget and situations like customs, documents, etc permits. Although, I have mailed the Hexagon (the GPS' owner company) for details and processses to bring it to India from Canada. I know the schematic is not completed yet but I started with the PCB. Again I have done some basic routing only. Here is the PCB gerber picture.

![PCB gerber]()

## Tasks completed today:

- Started with the PCB.
- Added custom symbols and footprints.
- Thinking to use [**NovAtel OEM-719**](https://novatel.com/products/receivers/gnss-gps-receiver-boards/oem719) as the GPS for satellite if budget and situation permits.

### Time spent today ~1.5h

---

# Day-4 (21/07/2025)

My journal was looking empty so I added pictures and a brief description of what work I did. I did not get much time today.

## Tasks completed today:

- Journaling (Added description and images).

### Time spent today ~0.5h