# LC-3 Virtual Machine

A fully functional LC-3 Virtual Machine written in C, capable of loading and executing LC-3 binary image files (`.obj`). This VM replicates the functionality of the LC-3 microarchitecture including memory, registers, instruction set, trap routines, and I/O interaction via the terminal.

## 🧠 About

The LC-3 (Little Computer 3) is a teaching architecture developed for learning assembly language and computer architecture principles. This project is a clean-room implementation of an LC-3 Virtual Machine capable of running compiled LC-3 programs (like a 2048 game, text editors, or other `.obj` files).

## ✨ Features

- Full 16-bit memory model (65,536 words)
- Complete support for all LC-3 instructions
- Keyboard I/O support through memory-mapped registers
- Terminal input/output handling
- Byte-swapping for cross-platform `.obj` file loading
- Instruction-level simulation loop
- Graceful interruption via `Ctrl+C` (SIGINT handling)

## 🔧 Requirements

- GCC or any C compiler
- Unix-like environment (macOS, Linux)

## Run Program
- ./main 2048.obj



