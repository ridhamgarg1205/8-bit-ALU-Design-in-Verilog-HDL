# 8-bit ALU Design in Verilog HDL

## Overview

This project implements a synchronous **8-bit Arithmetic Logic Unit (ALU)** using Verilog HDL. The ALU performs multiple arithmetic, logical, shift, and rotate operations controlled through a 4-bit select input. The design has been verified using a dedicated Verilog testbench and waveform simulation.

---

## Features

- 8-bit Data Width
- Synchronous Design
- Enable Controlled Operation
- Carry Flag
- Zero Flag
- Registered Outputs

---

## Supported Operations

| Opcode | Operation |
|---------|-----------|
|0000|Addition|
|0001|Subtraction|
|0010|Increment|
|0011|Decrement|
|0100|Multiplication|
|0101|Division|
|0110|AND|
|0111|OR|
|1000|XOR|
|1001|NAND|
|1010|NOR|
|1011|XNOR|
|1100|Shift Left|
|1101|Shift Right|
|1110|Rotate Right|
|1111|Rotate Left|

---

## Inputs

| Signal | Width | Description |
|---------|------|-------------|
|a|8-bit|Operand A|
|b|8-bit|Operand B|
|clk|1-bit|Clock|
|en|1-bit|Enable|
|s|4-bit|Operation Select|

---

## Outputs

| Signal | Width | Description |
|---------|------|-------------|
|y|16-bit|ALU Output|
|carry|1-bit|Carry Flag|
|zero|1-bit|Zero Flag|

---

## Simulation

The ALU functionality has been validated using a dedicated Verilog testbench.

Simulation verifies:

- Arithmetic operations
- Logical operations
- Shift operations
- Rotate operations
- Carry flag generation
- Zero flag generation

---

## Tools Used

- Verilog HDL
- ModelSim / QuestaSim
- GTKWave (optional)

---

## Future Improvements

- Overflow flag
- Signed arithmetic
- Parameterized ALU width
- Barrel shifter
- Status register
- Pipelined implementation

---

## Author
Ridham Garg
2024epb1276@iitrpr.ac.in
Engineering Physics  
Indian Institute of Technology Ropar
