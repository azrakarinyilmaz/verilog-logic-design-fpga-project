#Verilog Logic Design FPGA Project
This project was developed as part of a Digital Logic Design course.
The goal of the project is to design and simulate digital circuits using Structural Verilog, verify functionality with ModelSim, and implement the design on an FPGA using Quartus II.

#Project Components
The project consists of three main modules:
1. Logic Unit
- Implemented using structural Verilog
- Includes basic logic operations:
  - AND
  - OR
  - NAND
  - NOR
  - XOR
  - XNOR
  - NOT
2. Two-bit Binary Multiplier
- Multiplies two 2-bit binary numbers
- Implemented using logic gates
- Output is a 4-bit binary result
3. 7-Segment Display Decoder
- Converts binary output of the multiplier into a display format
- Displays the result on a 7-segment display on the FPGA board

#Tools Used
- Verilog HDL
- ModelSim (Simulation)
- Quartus II (FPGA Implementation)
- DE0 FPGA Board

#Simulation
Waveform simulations were performed in ModelSim to verify the correctness of the design.

#FPGA Implementation
The final design integrates the binary multiplier with the 7-segment decoder and runs on the DE0 FPGA board.
