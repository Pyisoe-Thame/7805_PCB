
# 7805 PCB design

This repository contains the PCB design files for a voltage regulator circuit based on the popular 7805 IC. The 7805 IC is a linear voltage regulator that provides a stable 5V output from a higher input voltage. Kicad is used to design the PCB.

The PCB has a Schottky diode for fast switching, several bypass capacitors and L7805CV IC, and last but not least, the screw terminals for universal input and output. 

The Schottky diode at the input side has maximum current rating of 1A and voltage drop of 0.45\~0.65V. The maximum output current is 1.5A; 7.5W in power. According to the datasheet, 7~35V without the aforementioned voltage drop is needed to satisfy the output. The electrolytic capacitor at the output side can be dumped as it is not found in the datasheet recommended circuit.

Note that there are other variants of 7805 IC that can only support output current of up to 1A.


## Features

- Compact Design: The PCB layout is optimized for a compact size, making it suitable for various projects where space is a constraint.
- Easy Integration: Designed with easy integration in mind, the PCB layout facilitates straightforward connection to input and output power sources and peripheral components.
- Versatile Application: Suitable for a wide range of applications requiring a regulated 5V power supply, including hobbyist electronics projects, prototyping, and small-scale production.


## Contents

- images/: The folder contains the screenshots taken by snipping tool to demonstrate the overview of what the product would look like.
- gerber files/: This directory contains the PCB design files in Gerber format, ready for fabrication.
- 7805.kicad_pcb: This is the actual PCB design file that controls the final product of the project.
- 7805.kicad_sch: Here, you'll find the schematic diagram of the voltage regulator circuit for reference.
- README.md: You're reading it right now! This file provides an overview of the project and instructions for usage.


## Screenshots

![Circuit Design](https://github.com/Pyisoe-Thame/7805_PCB/blob/master/images/7805_SCH.JPG)

![PCB Design](https://github.com/Pyisoe-Thame/7805_PCB/blob/master/images/7805_PCB.JPG)

![3D PCB](https://github.com/Pyisoe-Thame/7805_PCB/blob/master/images/7805_3D.JPG)


**Original Circuit Credit**:  
This project was inspired by [The Engineering Mindset](https://www.youtube.com/@EngineeringMindset)'s video titled [5V Regulator design tutorial](https://www.youtube.com/watch?v=d-j0onzzuNQ). While the original circuit served as inspiration, the PCB design in this repository is modified according to my own likeness, which I also am offering for free. Feel free to use and modify it as needed.


## License

This PCB design is provided under the [MIT](https://choosealicense.com/licenses/mit/) License, allowing for free use, modification, and distribution.