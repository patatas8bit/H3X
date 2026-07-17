# H3X
# H3X Language Interpreter
An esoteric programming language (esolang) developed by **hÆçĸ3ŗ** (patatas8bit), written in native ARM64 / AArch64 Assembly for Linux and Android Termux.

## Language Specifications & Rules
The H3X language operates on a single cell memory register (the standard ARM64 `x20` register). 
- **Initial Value:** The memory cell always starts at ASCII value `65` (Character 'A').
- **Cell Size:** 1 byte (8-bit value).

## Instruction Set
H3X consists of 4 core commands:
- `+` : Increments the current cell value by 1.
- `-` : Decrements the current cell value by 1.
- `.` : Outputs the ASCII character of the current cell value to `stdout`.
- `!` : Reads a single character from `stdin` and stores its ASCII value in the cell.
 
