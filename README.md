# Fluid Simulation

This repository contains an early C++/OpenGL particle-based fluid simulation experiment. The code was written as an exploratory graphics and simulation project, with particles rendered through OpenGL and spatial bookkeeping handled with a simple grid/box structure.

The project is kept mainly as an old code record. The source files have been moved to a direct `src/` layout so the repository is easier to browse.

## Project Structure

```text
.
|-- src/                  # C++ simulation and rendering source files
|   |-- Application.cpp
|   |-- Box.h
|   |-- COLOR.h
|   |-- Constant.h
|   |-- FluidSystem.cpp
|   |-- Particle.h
|   |-- mc_table.h
|   |-- test.cpp
|   `-- vendor/           # Header-only vendor files used by the original project
|-- Dependencies/         # Original GLEW/GLFW dependency folders
|-- .gitignore
`-- README.md
```

## Dependencies

The original project was developed as a Visual Studio/OpenGL program and used:

- OpenGL
- GLEW
- GLFW
- GLM

The `Dependencies/` and `src/vendor/` folders are kept from the original project structure.

## Notes

This is an early fluid-simulation exercise rather than a maintained application. The code is kept for reference, and the repository has been simplified so the main source files are visible directly under `src/`.