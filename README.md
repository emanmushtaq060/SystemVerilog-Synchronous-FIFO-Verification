# SystemVerilog-Synchronous-FIFO-Verification
8-bit × 16-entry synchronous FIFO designed and verified using SystemVerilog with OOP and constrained-random testing.

## Overview

This project implements and verifies an 8-bit × 16-entry synchronous FIFO using SystemVerilog.

The project includes:
- FIFO RTL design
- Object-oriented transaction class
- Constrained-random stimulus
- Self-checking testbench
- Expected-data reference queue
- Simulation waveform

## FIFO Features

- 8-bit data width
- 16-entry storage
- Synchronous read/write operation
- Read and write pointers
- Full and empty status flags
- Reset handling
- FIFO count tracking

## Verification

A SystemVerilog testbench was developed to verify the FIFO.

The testbench:
- Generates random FIFO transactions
- Uses an OOP transaction class
- Applies read/write operations to the FIFO
- Stores expected data in a reference queue
- Compares FIFO output with expected data
- Reports PASS/FAIL results

## Tools

- SystemVerilog
- EDA Playground
- EPWave

## Simulation Results

The testbench was simulated using QuestaSim.

### Simulation Output

![Simulation Output](images/simulation.png)

## Project Status

Completed:
- FIFO RTL design
- OOP transaction class
- Constrained-random stimulus
- Self-checking testbench
- Expected-data reference queue
