# Project 1 - Programing an ALU
In the first project we were tasked with programming a PAL to be able to make a range of aritmetic and logic operations. The ALU was given 2 inputs, A and B, each being 4 bit operands and the operation was selected by 3 selection bits. It would then present the result according expressed also in 4 bits taking into account the domain of the operands. It would also affect the Carry/Borrow out (CyBwo), Overflow (Ov) and Lesse Then Or Equal (LTE) flags, displying them as outputs.

The ALU was programmed to do the following operations:

- Arithmetic operations:
  - Addiction (000);
  - Subtraction (001);
  - Addiction with Carry (010);
  - Subtraction with Borrow (011);
- Logic operations:
  - Logic NOR bit-wise (1-0);
  - Logic Shift Left (1-1);
