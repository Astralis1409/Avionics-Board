  ### View latest KiCad files at [KiCanvas](https://kicanvas.org/?github=https://github.com/Jaydev-1510/Avionics-Board/tree/main/Hardware)

  ---

  # Day-1 (17/07/2025)

  This was the day I started this project. Feeling excited, I started with the block diagram. I was cofused thinking about the processor/OBC for the avionics board. At first, I thought of using some STM processor from the STM-F and STM-H series. At the same time I believed in the simplicity of using Raspberry Pi RP2040/2354. But they were not powerful for processing images and heandling telemetry at the same time. I liked the Raspberry Pi 5 module, but I could not use it as it was big. Then I got and idea of using Raspberry Pi CM5 a smaller version of Raspberry Pi 5. Finaly I chose Raspberry Pi CM5. I also explored various projects like the [PhoenixSat](https://phxcubesat.asu.edu/), [ORCAsat](orcasat.ca) and the CubeSat of [Build a CubeSat](youtube.com/@buildacubesat). Here is the block diagram I prepared.

  ![Block Diagram](https://github.com/user-attachments/assets/e4fa207e-1590-411f-93fb-bd6694553057)

  ## Tasks completed today:

  - Creation of repository and initial commits.
  - Surfing and research on other projects.
  - Creation of [**KiCad**](kicad.org) project.
  - Chose [**Raspberry Pi CM5**](raspberrypi.com/products/compute-module-5/) as the C&DH module and OBC.

  ### Time spent todday ~1.5h

  ---

  # Day-2 (18/07/2025)

  So, it were the IMU and the pressure sensor which were not finalised. After asking [ChatGPT](chatgpt.com) multiple times I decided to choose the ICM-20948 as the IMU because it was perfect for my application. It has got great precision and temperature range. Also I decided the pressure sensor as the [Bosch BMP390](https://www.bosch-sensortec.com/products/environmental-sensors/pressure-sensors/bmp390/). I thought of starting with the schematics. So, I started with it. By the way you can view the schematics and the PCB files at [KiCanvas](https://kicanvas.org/?github=https://github.com/Jaydev-1510/Avionics-Board/tree/main/Hardware) without downloading them! I have started with the basic connections as per the component's datasheets. I have added the schematic picture for your reference.

  ![Schematic](https://github.com/user-attachments/assets/12231ef5-8958-41b1-94a8-6f8c8fcf7894)

  ## Tasks completed today:

  - Started with the schematic.
  - [**Invensense ICM-20948**](https://invensense.tdk.com/products/motion-tracking/9-axis/icm-20948/) is now the IMU and magnetometer.
  - Also added [**Bosch BMP390**](https://www.bosch-sensortec.com/products/environmental-sensors/pressure-sensors/bmp390/) as the pressure sensor.

  ### Time spent todday ~2h

  ---

  # Day-3 (20/07/2025)

  The GPS of the cubesat will be attached to the avionics board only with the help of headers. After entering many prompts I am impressed by the [**NovAtel OEM-719**](https://novatel.com/products/receivers/gnss-gps-receiver-boards/oem719) and i think I will be able to use it if budget and situations like customs, documents, etc permits. Although, I have mailed the Hexagon (the GPS' owner company) for details and processses to bring it to India from Canada. I know the schematic is not completed yet but I started with the PCB. Again I have done some basic routing only. Here is the PCB gerber picture.

  ![PCB gerber](https://github.com/user-attachments/assets/ab482ff1-f5ca-4600-8b55-42e823b6d77f)

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

  # Day-5 (28/07/2025)

  First of all sorry for not working on the avionics board actively. Actualy [keyaan-07](https://www.github.com/keyaan-07) and I are working on an STM32H757IIT6 Dev board for hack club silicon. I came to know that I would not be able to use the Raspberry Pi CM-5 because of its heavy power consumption (12.5W at peak). Yep! that's too high. Therefore, I came up with an idea of making an STM32H757IIT6 Dev board so as I can learn about the STM32 processors, be familiar with the STM2 boards and gain some experience. I know I made a blunder but nevermind it's my first time making something huge. I will update about the dev board in next commit and this board is currently on hold. Sorry for the inconvenience. Btw [keyaan-07](https://www.github.com/keyaan-07) suggested me a kicad plugin (python) that converts the EasyEDA symbols and footprints to KiCad symbols and footprints even the 3D models! you can check out that repository [here](https://github.com/uPesy/easyeda2kicad.py).