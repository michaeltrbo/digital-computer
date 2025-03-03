**Overview**

In this project, we build fundamental logic gates using only the NAND gate. These gates form the building blocks of all digital circuits and serve as the foundation for the computer we will design in later projects.

**Gates Implemented**
- Basic Gates: NOT, AND, OR, XOR
- Multi-bit Versions: 16-bit implementations of these gates
- Control Gates: Multiplexers (Mux) and Demultiplexers (DeMux)

**Learning Outcomes**
- Understand how all logic gates can be built using only NAND.
- Develop hierarchical design skills by combining simple gates into complex circuits.
- Gain experience writing and testing hardware in HDL.

**Challenges & Solutions**
- Translating Logic to NAND: Using Boolean algebra and De Morgan’s laws to simplify expressions.
- Managing Complexity: Designing in a step-by-step, modular fashion.
- Testing & Debugging: Using the Hardware Simulator to verify correctness.

This project sets the stage for building arithmetic circuits, memory, and a full computer in later stages of the course.

**Files Structure**
~~~
project1/
│
├── And.hdl            # And gate implementation
├── And16.hdl          # 16-bit And gate
├── DMux.hdl           # Demultiplexer
├── DMux4Way.hdl       # 4-way demultiplexer
├── DMux8Way.hdl       # 8-way demultiplexer
├── Mux.hdl            # Multiplexer
├── Mux16.hdl          # 16-bit multiplexer
├── Mux4Way16.hdl      # 4-way 16-bit multiplexer
├── Mux8Way16.hdl      # 8-way 16-bit multiplexer
├── Not.hdl            # Not gate
├── Not16.hdl          # 16-bit Not
├── Or.hdl             # Or gate
├── Or16.hdl           # 16-bit Or
├── Or8Way.hdl         # 8-way Or
└── Xor.hdl            # Xor gate
~~~

**Logic Gate Derivation**

![image](https://github.com/user-attachments/assets/aa78db76-2c29-4e65-82b5-86685ec3115a)
