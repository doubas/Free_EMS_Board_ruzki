# FreeEMS Board 40 for FreeEMS


### Introduction

The aim of the FreeEms Board 40 is to provided a simple and small prototyping board for use with the FreeEms firmware but with the same pinout as the MegaSquirt-II daughterboard has. The FreeEms Board 40 is not mentioned to be a 1:1 replacement for the Megasquirt-II daughterboard. In comparison with the Megasquirt-II daughterboard the FreeEMS Baord 40 misses the IAC Idle Valve driver and has already pin 40 and 39 connected to the MCU (3rd and 4th injector), also know as the sequential mod.

Please see forum.diyefi.org for the most up to date information and links for this project and all of the other aspects of the FreeEMS project.

### Specs

Core IO specs:

 * 1  Freescale MC9S12XDP512 MCU 40MHz main core speed, 80MHz XGATE coprocessor, 32KB RAM, 512KB flash
 * 2  RPM/Position inputs
 * 10 Standard analog inputs (IAT or MAT,CLT,TPS,O2,BRV,MAF,AAP,MAP,one spare input).
 * 5  Available Port P PWM ports (PP1-3,PP5,PP7) access to PP1 and PP3 through a spare 2x1 pin connector
 * 2  ignitor outputs 
 * 4  injector outputs
 * 1  Fuel Pump output.
 * 4  PA2-PA6 logic channels as replacement for IAC1, IAC2, PE0 and PE1
 * 2  Reference voltage input Vref and Vsyn
 * 1  Serial RX TX communication port
 * 1  CAN communication through a MCP2551
 * 1  Load jumper for loading the FreeEms firmware without BDM
 * 1  BDM connector 

PCB size is held small as possible but wider as the Megasquirt-II daughterboard. Board size is (60mm x 38mm).  Most of the components are SMD parts but not smaller than SMD 0805 so the parts can be soldered with some practice by hand. 

To maintain a small PCB size the FreeEms 40 Board uses bended male precision PCB contacts, these can be made by careful bending the standard precision PCB contacts. Already bended precision PCB contacts can be bought e.g.. „Fisher Elektronik MK 26 SMD“. It is recommended to solder this pins by using a 40 pin precision socket as fixation. 

### Status

These Board is in alpha status, it has been tested on a test bench but not yet in a car at driving conditions. 


