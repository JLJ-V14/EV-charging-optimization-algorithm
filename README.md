Electric-Vehicles-Optimization is a C-based software library developed as part of my master’s thesis, designed to optimize the charging process of electric vehicles via a smart redistribution board. At its core is a customizable optimization algorithm powered by the OSQP solver, which ensures that each EV’s charging requirements are met efficiently.

Key features:

OSQP-Based Solver: Leverages the OSQP quadratic programming engine to satisfy EV charge constraints.

Extensible Objectives: Although currently tuned for EV charging, the algorithm can be adapted to optimize additional goals (e.g., cost minimization, load balancing, renewable integration).

Cross-Architecture Portability: Written in ISO-compliant C, the codebase compiles on any platform supported by the OSQP libraries (Linux, Windows, embedded systems, etc.).

Modular Design: Clear separation between model definition, solver interface, and hardware abstraction layers, facilitating easy customization and integration.

Whether you’re targeting large-scale charging stations or embedded controllers for smart grids, Electric-Vehicles-Optimization provides a flexible, high-performance foundation for advanced charging strategies.

This algorithm uses the OSQP solver libraries that are architecture dependent, so they must be compiled using CMake targetting the desired architecture. More information can be found in the following link: 

https://osqp.org/docs/index.html and their github: https://github.com/osqp/osqp.
