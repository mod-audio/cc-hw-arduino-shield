mod-arduino-shield
==================

This repository contains the schematics and PCB design files for the MOD Arduino Shield hardware. It serves as a way for people to create new peripheral to be used in conjunction with the MOD pedalboard (http://portalmod.com/) via its control-chain interface.

These files were created and can be improved with KiCAD, a free software Electronics CAD which is available at http://www.kicad-pcb.org/

## Check out instructions ##

This project uses a set of KiCAD pcb footprints created by the MOD dev-team (https://github.com/portalmod/mod-kicad-footprints). In order to properly fetch this dependency, which is configured as a "git submodule", you have to use the **--recursive** attribute in the following **git** command:

> git clone --recursive https://github.com/portalmod/mod-arduino-shield.git

## Licensing ##

This is an Open Hardware project and all of the files in this repository are licensed under the terms of the "Creative Commons By-SA" license.

## Sample Code / Arduino Library ##

There is an Arduino library for making it easy to develop your own Control-Chain MOD peripherals freely available at https://github.com/portalmod/mod-arduino-lib

