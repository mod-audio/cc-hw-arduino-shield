control-chain-arduino-shield
============================


This repository contains the schematics and PCB design files for Control Chain Arduino Shield hardware. It serves as a way for people to create new peripheral to be used in conjunction with MOD (http://moddevices.com/) via its Control Chain interface.

These files were created and can be improved with KiCAD, a free software Electronics CAD which is available at http://www.kicad-pcb.org/

## Check out instructions ##

This project uses a set of KiCAD symbols and footprints provided by the official KiCad library (https://github.com/KiCad/). In order to properly fetch these dependencies, which are configured as submodule repositories, you have to use the **--recursive** attribute in the following **git** command:

> git clone --recursive https://github.com/portalmod/control-chain-arduino-shield.git

## Licensing ##

This is an Open Hardware project and all of the files in this repository are licensed under the terms of the "Creative Commons By-SA" license.

## Sample Code / Arduino Library ##

There is an Arduino library for making it easy to develop your own Control Chain peripherals freely available at https://github.com/portalmod/control-chain-arduino-lib
