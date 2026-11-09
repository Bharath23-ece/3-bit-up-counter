# 3-Bit Up Counter using Verilog

## Objective
To design and simulate a 3-bit synchronous up counter using Verilog HDL.

## Description
A 3-bit up counter increments its binary count by one on every rising edge of the clock signal.

The counter has 3 flip-flop outputs and supports 8 states, ranging from 000 to 111.

## Features
- 3-bit binary counter
- Synchronous counting
- Asynchronous active-high reset
- Automatically rolls over from 111 to 000

## Counting Sequence

000 → 001 → 010 → 011 → 100 → 101 → 110 → 111 → 000

## Tools Used
- Verilog HDL
- Icarus Verilog
- GTKWave

## Files
- `up_counter.v` – RTL design
- `up_counter_tb.v` – Testbench

## Expected Result
The counter increments by one at every rising clock edge and resets to 000 when reset is asserted.
