# Brick Breaker (MASM x86 Assembly)

## Project Overview
For our Computer Organization and Assembly Language (COAL) project we made brick breaker game.The game was made in masm x86 and utilizes the `irvine32` library
and `winmm` for sound effects.
## Features
- **Three Levels**: Players progress through three increasing levels of difficulty.
- **File Handling**: The game reads and writes to three separate files for highscores:
  - `name.txt`: Stores player names.
  - `level.bin`: Tracks the current level.
  - `score.bin`: Records player scores.
- **Sound Effects**:
  - Background music plays during gameplay.
  - Brick-breaking sound effects enhance the experience.

## Requirements
- MASM x86 Assembly
- Irvine32 Library
- `winmm.lib` (Windows Multimedia Library)
- Windows OS (for compatibility with `winmm` functions)

## Installation & Setup
1. Install MASM and Irvine32 library.
2. Ensure `winmm.lib` is available in your linker settings.
3. Make sure to link your solution with irvine32 (provided in files)
4. Run the executable to start playing.

## Controls
- **A**: Move paddle left
- **D**: Move paddle right
- **W** Go Up (In menu)
- **S** Go Down (In menu)
- **Enter**: Start game
- **P**:Pause Game

## Contributors
- **Abdul Basit** - Roll Number:23i3018
- **Muhammad Inamullah** - Roll Number:23i-3058

## Notes
- The game requires the Irvine32 library for graphics and input handling.
- Ensure all required files (`name.txt`, `level.txt`, `score.txt`) are present in the same directory as the executable to prevent file errors.
- I have provided a sample video on how to run the game and install dependencies.
- If you have any questions or queries feel free to reach out to us!

Enjoy breaking bricks! 🚀

