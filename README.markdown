Introduction
------------

This project aims at creating a complete Open Source AVR based PIC programmer.

The target is to design a simple and extensible solution that enables AVR users to program PIC devices in few steps:

  - Grab any AVR device that 
   - can run on 3.3V
   - has at least 3 IO Pins
   - has at least 500b flash memory
   - can talk to PC via UART 
  - Download and burn in provided firmware
  - Connect it with PIC ISCP header according to schematics
  - Launch application and write/write program memory of PIC.

License
-------
All the documents are placed under the EUPL License which is compatible with most  open source licenses.

webLinux Updates
----------------
As the original version of this project seems to have fallen out of updating, I have renewed the effort. This version of the firmware will compile on the latest avr-gcc, and it now has a makefile! This should make the build process a lot easier.
