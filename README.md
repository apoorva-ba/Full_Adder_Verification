# Full_Adder_Verification
This project implements a 1-bit Full Adder using verilog and verifies its functionality

## Files
- full_adder.v : Adder design
- full_adder_tb.v : Testbench
- waveforms/full_adder.vcd
- README.md
- 
## Inputs
- a
- b
- cin 

## outputs 
- s
- cout

 ## Boolean equation
 - s = a ^ b ^ cin
 - cout = (a & b)|(b & cin)|(a & cin)

## Truth table
 | a | b | cin | s | cout |
 |---|---|-----|---|------|
 | 0 | 0 |  0  | 0 |  0  |
 | 0 | 0 |  1  | 1 |  0  |
 | 0 | 1 |  0  | 1 |  0  |
 | 0 | 1 |  1  | 0 |  1  |
 | 1 | 0 |  0  | 1 |  0  |
 | 1 | 0 |  1  | 0 |  1  |
 | 1 | 1 |  0  | 0 |  1  |
 | 1 | 1 |  1  | 1 |  1  |

## Author 

Apoorva B A
