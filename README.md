# Custom 3-bit CPU from Scratch

A complete 3-bit CPU designed and simulated at the gate level using the [Digital](https://github.com/hneemann/digital) logic simulator.

**Demo video:** https://youtu.be/PibiZZ_X_h8

## Specs

- **Word size:** 3 bits
- **ALU operations:** OR, ADD, SHR
- **Registers:** 4
- **RAM:** 9 words
- **Instruction/RAM word size:** 16 bits
- **Addressing modes:** Register, Immediate, Jump (JMP, JL)

## Components

- ALU (OR, ADD, SHR circuits)
- 4-register register file
- 9-word RAM
- Program counter
- Control unit
- Top-level CPU circuit wiring all of the above together

## Running it

Open the `.dig` files in [Digital](https://github.com/hneemann/digital). `CPU Architecture.dig` is the top-level circuit.
