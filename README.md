# navier

navier-stokes equation sandbox

A lightweight project for exploring fluid dynamics, numerical simulation, and visualization of the incompressible Navier–Stokes equations in a small, interactive sandbox.

## Current status

This repository is in an early scaffold stage. It is intended to grow into a small experimental environment for testing finite-difference or finite-volume ideas, visualizing flow fields, and exploring numerical stability.

## Goals

- Explore the incompressible Navier–Stokes equations in 2D and 3D
- Prototype numerical methods for advection, diffusion, and pressure solving
- Visualize velocity fields, vorticity, and streamlines
- Provide a simple sandbox for experiments and educational demos
- Keep the implementation readable, modular, and easy to extend

## Planned project structure

```text
navier/
├── README.md
├── requirements.txt
├── pyproject.toml
├── src/
│   └── navier/
│       ├── __init__.py
│       ├── grid.py
│       ├── solver.py
│       ├── visualization.py
│       └── utils.py
├── tests/
│   ├── test_solver.py
│   └── test_grid.py
└── examples/
    └── lid_driven_cavity.py
```

## Typical topics to explore

- incompressible flow
- Reynolds number scaling
- vorticity transport
- pressure correction methods
- projection methods
- stability constraints and CFL conditions
- visualization of flow patterns

## Getting started

This repo is intentionally a starting point. As the project evolves, the development flow is expected to look like this:

```bash
# create a virtual environment
python -m venv .venv
source .venv/bin/activate  # Linux/macOS
# or .venv\Scripts\activate  # Windows

# install dependencies
pip install -r requirements.txt

# run an example
python examples/lid_driven_cavity.py
```

## Recommended stack

A likely stack for this project includes:

- Python for numerical routines and experiments
- NumPy for array operations and linear algebra
- SciPy for solving PDE-related numerical problems
- Matplotlib for plotting and visual diagnostics
- Jupyter notebooks for exploration and teaching

## Roadmap

- set up project structure and dependency management
- implement basic grid utilities
- add advection and diffusion operators
- implement a simple incompressible solver
- add visualization to inspect velocity and pressure fields
- add tests for stability and correctness
- document examples and numerical assumptions

## Contributing

Contributions are welcome as the project matures. Potential areas of contribution include:

- numerical method implementations
- stability and performance improvements
- visualization tools
- documentation and examples
- tests and validation cases

## License

This project does not yet specify a license. Add one before publishing or distributing broader changes.

## Notes

This repository is a sandbox for experimentation and learning. The codebase and API will evolve as numerical techniques and project goals become clearer.
