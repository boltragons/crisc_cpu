# CRISC (Crabby RISC)

## The CRISC-1 CPU , or Crabby RISC, is a simplistic 8-bit RISC-based processor, made to learn and teach computer science subjects, such as “Computer Architecture”, “Digital Logic” and “Assembly Language”.

This processor was designed for the [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution) simulator.

![Simulator screenshot](https://github.com/boltragons/crisc_cpu/blob/main/docs/Simulator.png?raw=true)

The CPU has some major characteristics, such as:

- Four 8-bit general-purpose registers (R0 to R3).
- Harvard architecture (not modified) with separated I/O addressing space.
- 8-bit address bus width, being able to operate with up to 256 X 8-bit memories.
- 19 single-cycle simple instructions with up to two operands (destination and source).
- Conditional branching based on a zero flag generated by the ALU.
- 16 I/O software-controller registers, which enables up to five software-controlled GPIO ports (PORT A to PORT E), with 8 pins each (P0 to P7) and three registers for user interface.

For more info read the reference manual in the [docs/](https://github.com/boltragons/crisc_cpu/blob/main/docs) folder. Example codes are provided in [examples/](https://github.com/boltragons/crisc_cpu/blob/main/examples) folder.

A simple <b>assembler</b> was made for this CPU, the [CASM](https://github.com/boltragons/crisc_assembler/tree/main) (CRISC Assembler), in order to help with the learning process.
