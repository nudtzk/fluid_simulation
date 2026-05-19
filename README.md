# Fluid Simulation

This repository contains a personal OpenGL practice project by Zhang Kun. It implements a very simple particle-based fluid visualization demo using C++ and OpenGL.

The simulation is closest to a basic SPH-style particle fluid model rather than a grid-based Navier-Stokes solver. The code includes particle initialization, neighbor lookup with a simple spatial grid, density estimation with a smoothing kernel, pressure and viscosity terms, gravity, and OpenGL point rendering.

The project is kept as an early graphics and simulation exercise. The source files have been moved to a direct `src/` layout so the repository is easier to browse.

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

## Main Ideas

- OpenGL/GLFW window and point rendering
- 3D particle initialization
- Simple box/grid structure for neighbor search
- SPH-style smoothing radius and density kernel
- Pressure and viscosity force terms
- Basic boundary box visualization

## Dependencies

The original project was developed as a Visual Studio/OpenGL program and used:

- OpenGL
- GLEW
- GLFW
- GLM

The `Dependencies/` and `src/vendor/` folders are kept from the original project structure.

## Notes

This is an old personal OpenGL learning project. It is mainly useful as a record of early practice with particle simulation, OpenGL rendering, and basic SPH-style fluid mechanics code structure.
