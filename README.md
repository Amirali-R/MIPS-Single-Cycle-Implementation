# MIPS-Single-Cycle-Implementation

A single cycle implementation of 32-bit processor MIPS using Verilog

## Supported Instructions
### R-Format Instructuions
add, sub, addu, subu, and, or, xor, nor, slt, sltu
### I-Format Instructuions
 addi, addiu, slti, sltiu, andi, ori, xori, lui, beq, bne, lw, sw

 ## Some Notes
1. The exceptions related to instructions sub, addi, add are overlooked.
2. Every block used in the circuit is considered delayless.
3. The "building_blocks.v" file contains an asynchronous memory module and a register file module.
4. Two series of test bench files are also included for verification.
