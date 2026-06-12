# RTL Design and Functional Simulation of 8-Bit ALU

## Overview
This project implements an 8-bit Arithmetic Logic Unit (ALU) using Verilog HDL. The ALU performs arithmetic, logical, and shift operations based on a 3-bit select signal. Functional verification is carried out using a Verilog testbench and simulation.

## Features
- 8-bit Addition
- 8-bit Subtraction
- Bitwise AND
- Bitwise OR
- Bitwise XOR
- Bitwise NOT
- Left Shift
- Right Shift

## Tools Used
- Verilog HDL
- ModelSim / Vivado Simulator
- GTKWave (for waveform viewing)

## File Structure

RTL-Design-8Bit-ALU/
│
├── alu_8bit.v
├── alu_8bit_tb.v
├── README.md
└── simulation_results.png

## ALU Operations

| Select | Operation |
|----------|-----------|
| 000 | Addition |
| 001 | Subtraction |
| 010 | AND |
| 011 | OR |
| 100 | XOR |
| 101 | NOT |
| 110 | Left Shift |
| 111 | Right Shift |

## Verification
A dedicated testbench was created to verify all ALU operations. Simulation results confirmed correct functionality for arithmetic, logical, and shift operations.

## Learning Outcomes
- RTL Design using Verilog HDL
- Combinational Logic Design
- Functional Verification
- Testbench Development
- Digital Circuit Simulation

## Author
Hiranya Vaddemani

## Internship Task
Task 1 – RTL Design and Functional Simulation using Verilog HDL.
