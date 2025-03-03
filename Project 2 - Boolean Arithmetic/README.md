**Overview**

In this project, we expand upon the foundational logic gates developed in Project 1 to construct essential arithmetic circuits. These components are vital for performing arithmetic operations within a computer system and serve as the building blocks for the Arithmetic Logic Unit (ALU) that will be designed in this project.

**Components Implemented**

Half Adder: Computes the sum and carry of two single-bit binary numbers.
Full Adder: Extends the half adder to include carry-in, enabling multi-bit addition.
Add16: Performs 16-bit addition by chaining multiple full adders.
Incrementer (Inc16): Increases a 16-bit binary number by one.
Arithmetic Logic Unit (ALU): Combines arithmetic and logical operations into a single component, capable of performing functions like addition, bitwise operations, and conditional negation.

**Learning Outcomes**

Binary Arithmetic: Gain a deeper understanding of binary addition and the significance of carry bits.
Modular Design: Learn to construct complex circuits by integrating simpler components, emphasizing the importance of modularity in hardware design.
ALU Functionality: Understand the role of the ALU in executing arithmetic and logical operations within the CPU.
Challenges & Solutions

Carry Propagation: Managing carry bits across multiple bits in addition operations can be complex. Implementing structured designs, such as cascading full adders, ensures accurate carry propagation.
Component Integration: Combining various arithmetic and logical functions into a single ALU requires careful planning. Utilizing multiplexers to select desired operations based on control signals facilitates this integration.
Testing Complex Circuits: As circuits become more intricate, thorough testing is essential. Developing comprehensive test scripts and utilizing simulation tools help validate functionality and identify issues.
This project builds upon the basic logic gates from Project 1, advancing towards the creation of a functional CPU by establishing the arithmetic capabilities necessary for computation.

**File Structure**

The project directory contains the following Hardware Description Language (HDL) files:
~~~
project2/
│
├── HalfAdder.hdl       # Implementation of the half-adder
├── FullAdder.hdl       # Implementation of the full-adder
├── Add16.hdl           # 16-bit adder
├── Inc16.hdl           # 16-bit incrementer
└── ALU.hdl             # Arithmetic Logic Unit
~~~

**Thought Process**

![image](https://github.com/user-attachments/assets/aaba706b-41fa-4bec-bc64-921befcd53c0)
