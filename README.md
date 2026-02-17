# cub3D - Raycasting Engine in C

## Project Overview
**cub3D** is a 42 school project that recreates a "3D" graphical view of a maze using the **Raycasting** algorithm, similar to the original **Wolfenstein 3D**. 

This project was developed and tested on **Linux (Ubuntu/Debian)**.

## Features
- **Real-time Rendering:** Fluid 3D navigation
- **Raycasting Algorithm:** Precise wall distance calculation to simulate a 3D view.
- **Texture Mapping:** Side-specific textures (North, South, East, West).
- **Collision Detection:** Prevents the player from walking through walls.
- **Event Handling:** Seamless window management and keyboard inputs via X11.

## Technical Stack
- **Language:** C (using C98).
- **Graphics:** MiniLibX (Linux version using X11 and Shm).
- **Environment:** Linux / WSL2.
- **Math:** Trigonometry, Vector Geometry, and Linear Algebra.

## Linux Setup & Requirements
To compile and run this on a Linux environment, you need the following dependencies:
```bash
sudo apt-get update
sudo apt-get install build-essential libx11-dev libxext-dev libbsd-dev
```

## Compile and run
To compile just execute
```
make
./cub3D maps/"some map"
```
## Other useful commands
```
make clean
make fclean
make re
```
