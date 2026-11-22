# PATTERN-DETECTION-USING-FPGA
FPGA-Based DNA Pattern Detection System

Overview

This project implements a DNA pattern detection system using Verilog HDL on an FPGA. It detects a specific DNA sequence from encoded nucleotide inputs using digital logic.

DNA Encoding

Each nucleotide is represented using 2-bit binary encoding:

- A (Adenine) – 00
- T (Thymine) – 01
- C (Cytosine) – 10
- G (Guanine) – 11

Working Principle

The DNA sequence is provided through input switches. The FPGA processes the encoded bases and compares them with a predefined DNA pattern. When the target pattern is detected, the output signal indicates a successful match.

Features

- FPGA-based real-time pattern detection
- 2-bit DNA nucleotide encoding
- Verilog RTL implementation
- Simulation using a Verilog testbench
- Designed and developed using Xilinx Vivado

Applications

This project demonstrates the use of digital hardware for basic genomic sequence analysis. It can be extended for DNA motif detection, bioinformatics hardware acceleration, and biomedical signal processing applications.

Future Scope

Future improvements include detecting longer DNA sequences, configurable patterns, UART-based sequence input, and displaying detection results through LEDs or an LCD.

Tools

Verilog HDL, Xilinx Vivado, FPGA development board.
