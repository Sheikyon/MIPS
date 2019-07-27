# A minimal MIPS simulator in Rust

A software simulator (fetch-decode-execute) of a MIPS processor in a very low-level execution environment, bordering on bare-metal. This is inspired by the EE182 Programming Assignment #2 brief from Stanford University. If you are interested, click [here](https://web.stanford.edu/class/ee182/Projects/PA2/pa2.html) to see what it's about.

The purpose of this project is to explore the MIPS architecture in its lowest-level abstraction (bare-metal), without an operating system or a high-level runtime environment. Just plain low-level code.

This project was also used as a demonstration of the complexity and presence of bloat in x86 compared to other architectures.

# What includes

1. MIPS machine code execution (fetch-decode-execute),
2. Memory simulator (without memory management or garbage collection), 
3. Simulation of the 32 general-purpose registers of the architecture,
4. Handling instruction cycles,
5. etc.