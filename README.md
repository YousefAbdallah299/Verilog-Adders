# Verilog Adders

## Description

This repository contains Verilog implementations of various types of adders commonly used in digital circuit design. Adders are fundamental building blocks in computational hardware, enabling arithmetic operations like addition, subtraction, and more. The adders included in this project are designed to optimize performance.

## Features

- **Modular Design**: Each adder is implemented as a standalone module.
- **High Efficiency**: Optimized for both synthesis and simulation.
- **Comprehensive Testing**: Each module includes a corresponding testbench for validation.
- **Scalable**: Supports parameterization for different bit widths.

## Adders Included

1. **Half Adder**:
   - A simple 1-bit adder that adds two single bits and produces a sum and a carry-out.
2. **Full Adder**:
   - A 1-bit adder that adds three bits (two inputs and a carry-in) and produces a sum and a carry-out.
3. **Ripple Carry Adder**:
   - Combines multiple full adders to add multi-bit numbers.
4. **Carry Lookahead Adder**:
   - Improves performance by reducing the delay caused by carry propagation.
