# MIPS processor in Simulink

This is the implementation of single-cycle MIPS processor in Simulink.
It closely follows the MIPS microarchitecture described in "Digital Design and
Computer Architecture" by David Money Harris and Sarah L. Harris.
This design can be simulated in Simulink and converted automatically to HDL using HDL Coder.

## Supported instructions:
* add
* sub
* and
* or
* slt
* addi
* lw
* sw
* beq
* j

The instruction memory is preloaded with a sample program from the same book.