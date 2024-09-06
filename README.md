# Simulator
Designing and Implementing the simulator.
The input for the simulator is the binary file converted by the assembler. The simulator, after the
execution of every instruction, prints the register values in any chosen file. The simulator will print
the memory stats after the execution of the mentioned Virtual Halt instruction.
Output format to be stored in the chosen file after execution of every instruction. If you have
not implemented the yellow colored registers store the value ”0” in their place.
{Program Counter}{Space}{x0}{Space}{x1}{Space}{x2}{Space}..............{Space}{x31}
The memory at the simulator side should be of size (32X32-bit). The output will have all the
memory content (32 lines) printed starting from address (0x0000 0000). Output format of memory
after the execution of Virtual Halt.
32-bit binary data
32-bit binary data
32-bit binary data
.
.
.
32-bit binary data
