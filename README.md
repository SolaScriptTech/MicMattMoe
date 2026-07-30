# MicMattMoe

A playful command-line Tic-Tac-Toe game written in C++. You play as **M** against a deliberately "not so good" computer playing as **O**.

## Features

- Random selection of the starting player
- Input validation
- Winner detection across rows, columns, and diagonals
- Replay support
- A deliberately unpredictable computer opponent
- Portable CMake build configuration

## Build

### CMake

```sh
cmake -S . -B build
cmake --build build
```

Run the resulting `MicMattMoe` executable from the build directory.

### Single compiler command

```sh
g++ -std=c++17 -Wall -Wextra -pedantic src/MicMattMoe.cpp -o MicMattMoe
```

## How to play

Choose positions 1 through 9. The first player to place three matching marks horizontally, vertically, or diagonally wins.

## Project origin

MicMattMoe began as a CISP 360 coursework project and was later extracted from the [Random-.cpp](https://github.com/SolaScriptTech/Random-.cpp) learning archive into its own repository.

## License

[MIT](LICENSE)
