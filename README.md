# Jack Tetris - A Tetris Game in Jack Language

This repository contains a simple implementation of the classic Tetris game using the Jack programming language, as described in Chapter 9 of the [Nand to Tetris](https://www.nand2tetris.org/) course. Jack is a high-level language that can be compiled to VM code and run on the Hack platform.

## Prerequisites

To build and run this Tetris game, you'll need the following tools:

- **Jack Compiler:** You can compile the Jack code in this repository to VM code using the Jack Compiler, which is provided as part of the [Nand to Tetris](https://www.nand2tetris.org/) software suite.

- **VM Emulator:** You'll need a VM emulator capable of running the generated VM code. You can use the provided VM emulator from the [Nand to Tetris](https://www.nand2tetris.org/) suite or any compatible emulator.

## Installation

To run the Tetris game, follow these steps:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/cuspymd/jack-tetris.git
cd jack-tetris
```

2. Compile the Jack source files into VM code using the Jack Compiler. Make sure to use the appropriate commands provided in the [Nand to Tetris](https://www.nand2tetris.org/) course to compile your Jack code.
3. Load the generated VM code into your VM emulator.
4. Start the emulator to play the Tetris game!

## Game Controls

Use the arrow keys to move and rotate the falling Tetriminos. The goal is to complete lines by filling them with Tetriminos to score points and prevent the screen from filling up.
