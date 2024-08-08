# EMUSNESV0
7.8.24$ - EMUSNES
# EMUSNES

EMUSNES is a Super Nintendo Entertainment System (SNES) emulator written in C using SDL2 and SDL2_ttf. It aims to provide accurate emulation of SNES games with support for rendering at 60 frames per second.

## Features

- **60 FPS Rendering**: Provides smooth gameplay with accurate timing.
- **Font Support**: Loads Times New Roman font from various paths for rendering text.
- **Basic CPU and Memory Emulation**: Implements core SNES CPU and memory management.

## Prerequisites

To build and run EMUSNES, you need the following:

- **SDL2**: The Simple DirectMedia Layer 2 library.
- **SDL2_ttf**: The SDL2 extension for font rendering.
- **gcc** or **clang**: A C compiler.

### Installation on macOS (with Homebrew)

1. Install Homebrew if you haven't already:
    ```bash
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```

2. Install SDL2 and SDL2_ttf:
    ```bash
    brew install sdl2 sdl2_ttf
    ```

## Building the Emulator

1. Clone the repository:
    ```bash
    git clone https://github.com/snakesychanftw/EMUSNESV0.git
    cd EMUSNESV0
    ```

2. Compile the code:
    ```bash
    gcc -o emusnes emusnes.c -I/opt/homebrew/opt/sdl2/include -I/opt/homebrew/opt/sdl2_ttf/include -L/opt/homebrew/opt/sdl2/lib -L/opt/homebrew/opt/sdl2_ttf/lib -lSDL2 -lSDL2_ttf
    ```

## Running the Emulator

To run the emulator, execute the following command:

```bash
./emusnes
