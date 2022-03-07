# Computer-architecture-
A simulation of a fictional processor design and architecture using Java.

# Memory Architecture :
  1. Architecture: Harvard
    • Harvard Architecture is the digital computer architecture whose design is based on the concept
where there are separate storage and separate buses (signal path) for instruction and
data. It was basically developed to overcome the bottleneck of Von Neumann Architecture.
  b) Instruction Memory Size: 1024 * 16

# Data Memory 
  1. Size: 2048 * 8
  2. The data memory addresses are from 0 to 211 􀀀 1 (0 to 2047).
  3. Each memory block (row) contains 1 word which is 8 bits (1 byte).
  4. The data memory is word/byte addressable (1 word = 1 byte).
  5. The data is stored in the data memory.
  
# Registers: 66
 1. Size: 8 bits
 2. 64 General-Purpose Registers (GPRS)
 3. 1 Status Register
   The status register has 5 flags updated after the execution of specific instructions:
     * Carry Flag (C) .
     * Negative Flag (N) .
     * Sign Flag (S) .
  • 1 Program Counter
      – Name: PC
      – Type: Special-purpose register with a size of 16 bits (not 8 bits).
      – A program counter is a register in a computer processor that contains the address (location)
        of the instruction being executed at the current time.
       – As each instruction gets fetched, the program counter is incremented to point to the next
        instruction to be executed.
