# DSKY-Project
My open source journey to building a functional DSKY that can be used in simulator. 
 
## v1 Hardware
 - Raspberry Pi 3B+ running VirtualAGC + driving the display & keyboard
 - Nextion 4.3" LCD HMI (NX4827T043_11) display
 - Alarm Panel PCB designed by Riley Rainey
 - CherryMX Blue switches for keyboard
 - 3D Printed shell components made from models created by Riley Rainey from original MIT drawings
 
## Software
 - Drivers for display, alarm panel & keyboard written in Python3
 - VirtualAGC project
 - Project Apollo - NASSP
 
## Setup
Raspberry Pi running VirtualAGC is driving the Nextion HMI, sending lamp instructions to the Alert board and reading keystrokes from Keyboard

## Task List
- [x] Build working GUI for HMI display
- [x] Driver for Nextion HMI display
- [x] Assemble alarm panel PCB
- [x] Driver for alarm panel
- [ ] Assemble keyboard (In Progress)
- [ ] Code for Keyboard (In progress)
- [ ] Update piDSKY2.py file (In Progress)
- [ ] Fix bugs in code
- [ ] Refine GUI to more closely match original DSKY display
- [ ] Assemble DSKY
- [ ] Test with VirtualAGC + NASSP

## References
 [VirtualAGC Project](https://www.ibiblio.org/apollo/) - I am so thankful that this exists because it has been my dream to build my own DSKY ever since I first learned of the
 project\
 [Riley Rainey](https://github.com/rrainey) - His amazing work in designing the alert and keyboard PCBs, modeling the DSKY shell and inner components from original drawings gave
 me the opportunity to start this project\
 [Manoel DaSilva](https://github.com/ManoDaSilva) - He created the HMI file which I modified and adapted to my code
