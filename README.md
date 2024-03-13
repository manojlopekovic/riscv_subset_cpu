# riscv_subset_cpu

### Used tools 
Programmed in Makerchip IDE, with TL-Verilog

### Startup code
Using starting code from https://makerchip.com/sandbox?code_url=https:%2F%2Fraw.githubusercontent.com%2Fstevehoover%2FLF-Building-a-RISC-V-CPU-Core%2Fmaster%2Frisc-v_shell.tlv#

## RISC-V CPU
RISC-V CPU Block diagram
![image](https://github.com/manojlopekovic/riscv_subset_cpu/assets/97803831/2b1cb63e-2b8c-4a36-94a4-6ed83dff7e7c)
  
1. PC Logic - Sequentiall, branch and jump pc changes
2. Fetch logic - from instruction memory, using makerchip readonly macro
3. Decode logic - interpretation of current instruction
4. Register file read - using m4 register file module
5. ALU unit
6. Register File write
7. Data Memory - using m4 memory model
