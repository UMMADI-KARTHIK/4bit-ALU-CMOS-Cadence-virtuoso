4-bit ALU Design in Cadence Virtuoso

📌 Project Overview

This project implements a 4-bit Arithmetic Logic Unit (ALU) using transistor-level CMOS design in Cadence Virtuoso.
The ALU supports 8 fundamental operations:

AND

NAND

OR

NOR

XOR

XNOR

ADD (with carry-in & carry-out)

SUBTRACT

⚡ Design Flow

Basic Gates: Designed AND, OR, NAND, NOR, XOR, and XNOR using CMOS transistor-level logic.

Arithmetic Blocks: Implemented 1-bit Full Adder and 1-bit Subtractor at transistor level.

1-bit ALU: Used a 2:1 MUX hierarchy to select one of the 8 operations.

4-bit ALU: Connected four 1-bit ALUs in ripple-carry configuration for addition and subtraction.

Simulation: Verified outputs with Spectre transient analysis using pulse and DC input sources.
