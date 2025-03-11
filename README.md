# Conway's Game of Life

This is a simple implementation of Conway's Game of Life in Mojo. 

## What is Mojo?
It is a new language that is designed to be a superset of Python. It's easy to learn, because it has the same syntax as Python, but it also has some features that make it more powerful. For example, it has a built-in build system, so you can easily compile your code into a binary. And it has a built-in package manager, so you can easily share your code with others. It also allows access from Python libraries, so you can use all the libraries that are available for Python. The language is still in development, but it is already quite powerful and easy to use.

## Description
The game is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input. One interacts with the Game of Life by creating an initial configuration and observing how it evolves.

The game is a grid of cells, each cell can be either alive or dead. The game evolves in steps, where each step the following rules are applied:
1. Any live cell with fewer than two live neighbors dies, as if by underpopulation.
2. Any live cell with two or three live neighbors lives on to the next generation.
3. Any live cell with more than three live neighbors dies, as if by overpopulation.
4. Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.

You can find more information about the code [here](https://docs.modular.com/mojo/manual/get-started/). 

## Technologies and more information
<img src="https://img.shields.io/badge/Mojo-EA8220?style=for-the-badge&logo=fireship&logoColor=red" alt="Mojo" />
<img src="https://img.shields.io/badge/Unlicense-green?style=for-the-badge&logo=unlicense&logoColor=white" alt="Modular" />
<img src="https://img.shields.io/badge/Conway's Game of Life-FF6D5A?style=for-the-badge&logo=game&logoColor=white" alt="Conway's Game of Life" />
<img src="https://img.shields.io/badge/Zero-Player Game-FF6D5A?style=for-the-badge&logo=game&logoColor=white" alt="Zero-Player Game" />

## How to run the code
To run the code, you need to have the Mojo CLI installed.
```bash
curl -ssL https://magic.modular.com/2b3b76c4-24e7-42fc-a68c-8f392ff181bc | bash
```

Clone the repository and navigate to the directory.
```bash
git clone https://github.com/CKnuchel/GameOfLife.git

cd GameOfLife
```

Switch to the Mojo environment.
```bash
magic shell
```

Run the code.
```bash
mojo run life.🔥
```


Or build a binary and run it.

Make sure you have the required dependencies installed. For building a binary you need to have a C++ compiler installed. You can install it by running the following command.
```bash
sudo apt update
sudo apt-get install build-essential zlib1g-dev libtinfo-dev
```

```bash
mojo build life.🔥
./life
```

### Additional information
If you want to learn more about Mojo, you should get through the tutorial by yourself. [Tutorial](https://docs.modular.com/mojo/manual/get-started/).
