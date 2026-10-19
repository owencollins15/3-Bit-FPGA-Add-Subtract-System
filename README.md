# 3-Bit-FPGA-Add-Subtract-System
VHDL-based 3-bit add/subtract system for the DE1-SoC FPGA with synchronized inputs, edge detection, seven-segment display output, and ModelSim verification.


This project implements a 3-bit hardware addition and subtraction system in VHDL for the DE1-SoC FPGA development board. The design accepts two 3-bit inputs through slide switches, synchronizes external inputs to the board’s 50 MHz clock, and performs addition or subtraction based on push-button input. Input values and the resulting 4-bit output are displayed using the board’s seven-segment displays. The design was verified in ModelSim by testing input combinations and simulating both add and subtract operations before being implemented on hardware.
