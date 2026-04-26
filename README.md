# Project README

## Overview
This project is a C/C++ application that demonstrates Optical Flow detection using AR (Augmented Reality). The application uses a sprite-based approach to track optical flow and render images on the screen.

## Features
- Optical Flow Detection
- Augmented Reality rendering
- Cross-platform compilation for Linux, Windows, Wine, and WebAssembly

## Project Structure
### Prerequisites
- C/C++ Compiler and Debugger (GCC, Clang)
- Make utility
- Standard development tools
- Libraries needed in specific projects:
  - X11 for Linux
  - WINAPI for Windows
  - WINE for Windows cross-compilation
  - Emscripten for WebAssembly

## Build & Run
### Linux
To build and run the project on Linux, use the following commands:

```sh
cd /path/to/project
make -f Makefile.linux all
make -f Makefile.linux exe
```

### Windows
To build and run the project on Windows, use the following commands:

```sh
cd /path/to/project
make -f Makefile.windows all
make -f Makefile.windows exe
```

### Wine
To build and run the project using Wine for Windows cross-compilation, use the following commands:

```sh
cd /path/to/project
make -f Makefile.wine all
make -f Makefile.wine exe
```

### WebAssembly (Emscripten)
To build and run the project on WebAssembly, use the following commands:

```sh
cd /path/to/project
make -f Makefile.web all
make -f Makefile.web exe
```

By running `make -f Makefile.(os) do`, you can perform a clean build followed by executing the program.