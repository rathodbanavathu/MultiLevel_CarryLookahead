# Carry Look-Ahead Adder (CLA)

A high-speed binary adder in Verilog using **generate** and **propagate** signals.  
Designed to reduce carry propagation delay compared to a ripple-carry adder.

## Features
- Parameterized bit-width (default: 32-bit).
- Fast carry generation with O(log N) delay.
- Synthesizable RTL design.
- Verified with functional testbenches.
