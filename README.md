# RV32I Single-Cycle RISC-V Processor

A complete RTL implementation of a 32-bit Single-Cycle RV32I RISC-V Processor developed in Verilog HDL.

The processor follows a Harvard Architecture and supports the base RV32I instruction set including arithmetic, logical, memory access, and branch instructions. The design is functionally verified using Icarus Verilog and GTKWave.

---

## Project Overview

This project implements a Single-Cycle RISC-V Processor capable of executing RV32I instructions in one clock cycle.

The architecture includes:

- Program Counter (PC)
- Instruction Memory
- Immediate Generator
- Register File
- Control Unit
- ALU Control
- Arithmetic Logic Unit (ALU)
- Data Memory
- Performance Counter Unit (PCU)

A custom Performance Counter Unit (PCU) has been integrated to monitor processor execution statistics in hardware.

---

## Features

✅ RV32I Base ISA Support

✅ Harvard Architecture

✅ Single-Cycle Execution Model

✅ Modular RTL Design

✅ Hardware Performance Counter Unit

✅ Functional Verification using Icarus Verilog

✅ GTKWave Simulation Analysis

✅ Extensible Architecture for Future Enhancements

---

## Architecture

Processor Datapath:

Instruction Fetch
→ Decode
→ Execute
→ Memory Access
→ Write Back

All operations complete in a single clock cycle.

---

## Supported Instruction Categories

### R-Type

- ADD
- SUB
- AND
- OR
- XOR
- SLL
- SRL
- SRA
- SLT
- SLTU

### I-Type

- ADDI
- ANDI
- ORI
- XORI
- SLTI
- SLTIU
- SLLI
- SRLI
- SRAI
- LW
- LH
- LB
- LHU
- LBU
- JALR

### S-Type

- SW
- SH
- SB

### B-Type

- BEQ
- BNE
- BLT
- BGE
- BLTU
- BGEU

---

## Performance Counter Unit (PCU)

The processor includes a dedicated PCU that tracks:

- Total Clock Cycles
- Instructions Executed
- R-Type Instructions
- Load Instructions
- Store Instructions
- Branch Taken Instructions

The PCU provides hardware-level performance monitoring without software overhead.

---

## Tools Used

| Tool | Purpose |
|--------|----------|
| Verilog HDL | RTL Design |
| Icarus Verilog | Simulation |
| GTKWave | Waveform Analysis |
| GitHub | Version Control |

---

## Project Structure
