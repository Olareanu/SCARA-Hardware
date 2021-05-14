# SCARA-Hardware

SCARA Hardware is a repository that contains a hardware description of Olăreanu Alexndru 's educational SCARA Robot. For More information see the main repository here:

[SCARA-Master](https://github.com/Olareanu/SCARA_Master)

## Introduction
SCARA stands for Selective Compliance Articulated Robotic Arm. Such arms usually have multiple segments linked one after the other to facilitate movement on X and Y axes and an additional Z axis perpendicular to those (although many types of geometries exist.)

The aim of this project is to design, build and program a 2 axis SCARA Robot. The robot should be controlled trough standard Gcode sent from a computer.

The electronics are custom designed and manufactured with easyEDA and JLCPCB with additional parts from Mouser Electronics. 
Most of the Hardware is 3D printed on a Prusa I3 Mk3 Printer, mostly with Prusament. Some parts, like 8mm Rods, nuts and bolts were sourced locally. Stepper Motors from StepperOnline. Everything was designed in CAD using Fusion360.

The code runs on an STM32F411CE Black Pill Microcontroller and is compiled using PlatformIO in CLion. The C++ programming language is used.

## License
The Code is under GPLv3 License. Please ask permission for the use of the Hardware. Working with electronics is dangerous. Olăreanu Alexandru is not responsible for liabilities.