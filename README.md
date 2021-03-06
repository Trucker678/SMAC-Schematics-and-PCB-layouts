# SMAC Schematics and PCB Layouts

## Introduction
This repository contains schematics and board layouts for all of SMAC modules and development platforms.

Design files can be opened with CadSoft EAGLE PCB Design Software, freely available for Windows, Linux and OSX platform from http://www.cadsoftusa.com/download-eagle/?language=en

## List of Modules

Module Name | Type | Function | IC  | Diameter [mm] | Ion [mA] | Ioff [mA]
:---------: | :--: | :------: | :-: | :-----------: | :------: | :------:
[Master](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Master) | Master | CPU and wireless communication | CC2530  | 9.8  | 34 | 0.5
[3DA](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Digital-Sensing/3DA) | Digital Sensing | 3D Accelerometer | LIS331DLH  | 9 | 0.25 | 0.01
[3DG](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Digital-Sensing/3DG) | Digital Sensing | 3D Gyroscope | L3GD20 | 9 | 6.1 | 0.005
[3DM](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Digital-Sensing/3DM)| Digital Sensing | 3D Magnetometer | LIS3MDL | 9 | 0.27 | 0.001
[3DAG](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Digital-Sensing/3DAG) | Digital Sensing | 3D Accel./Gyro. | LIS330DLC | 9.8 | 6.11 | 0.005
[3DAM](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Digital-Sensing/3DAM) | Digital Sensing | 3D Accel./Magnet. | LSM303D | 9.8 | 0.3 | 0.001
[3DAMG](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Digital-Sensing/3DAMG) | Digital Sensing | 3D Accel./Magnet./Gyro. | LSM9DS0 | 9.8 | 6.15 | 0.005
[PT](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Digital-Sensing/PT) | Digital Sensing | Pressure/Temperature | MPL115A1 | 9.8 | 0.005 | 0.001
[8ADC](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Analog-Sensing/8ADC) | Analog Sensing | 8 Channels ADC | AD7689 | 9.8 | 03.78 | 0.005
[2AFADC](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Analog-Sensing/2AFADC) | Analog Sensing | 2 Channels Front End & ADC | AD623 & ADS8320  | 9.8 | 2.57 | 0.001
[BSDCC](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Actuation/BSDCC) | Actuation | Brushed DC Motor Controller | A3901 | 9.5 | - | 0.005
[BSLDCC](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Actuation/BSLDCC) | Actuation | Brushless DC Motor Controller | BH67172NUX | 9.8 | - | 0.009
[VI](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Vision-Illumination/VI) | Vision/Illumination | Vision/Illumination | NUD533 | 9.8 | 150 (Max) | -
[PMM](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Power-Management/PMM) | Power Management | Power/Battery Monitor | TPS33 | 9.8 | 500 (Max) | -

## List of Development Kits

Devkit name | Features | Dimension [mm]
:---------: | :------: | :------------:
[CC2530EV](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Development-Boards/2530EV) | CC2530F256, Debugger connector, 2x 8p interface headers, 1x power headers, 1x reset button | 40 x 40
[SMAC-2530](https://github.com/SMACproject/SMAC-Schematics-and-PCB-layouts/tree/master/Development-Boards/SMAC-2530) | CC2530F256, FT230x USB to serial converter, CC Debugger connector, 2x 10p interface headers, 3x power headers, 1x LCD3310 interface, 4x LEDs, 1x push button, 1x reset button | 62.5 x 57.5