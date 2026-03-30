# GhidraMn10300

unfinished processor module for mn10300.

bit of a "fix as i go" kinda state, works for most stuff. Unsure about accuracy. (probably doesnt work well for fpu instructions)

Lots of instructions have been stubbed out.

token structure is a bit of a mess imo. should have better seperation between base mn10300 and am33 and am33-2, but its whatever.

## Refrences

- losely based of [Pokechu22/shizmob ghidra-mn102](https://github.com/shizmob/ghidra-mn102)
- [MN1030/MN103S Series Instruction Manual](https://www.bitsavers.org/components/panasonic/panaXseries/13250-040E_MN1030_MN103S_Series_Instruction_Manual.pdf) (base mn10300 spec, lacking alot of am33 things) NOTE: this one has alot of small annoying mistakes.
- [binutils disassembler opcode listing](https://sourceware.org/git/?p=binutils-gdb.git;a=blob;f=opcodes/m10300-opc.c) (incomplete)
- [binutils igen listings](https://sourceware.org/git/?p=binutils-gdb.git;a=tree;f=sim/mn10300) in am33-2.igen, am33.igen and mn10300.igen

i think use of binutils would make this GPL licenced in some way. Respect the references.
