---
layout: default
title: Code
---

Tools developed by the group:

### bsym

[bsym: A Basic Symmetry Module](https://github.com/bjmorgan/bsym) is a basic Python symmetry module. It consists of core classes that describe configuration vector spaces, their symmetry operations, and specific configurations of objects within these spaces. The module also contains an interface for working with [`pymatgen`](http://pymatgen.org) `Structure` objects, to allow simple generation of disordered symmetry-inequivalent structures from a symmetric parent crystal structure.

### pyscses
 
[pyscses](https://github.com/georgiewellock/PYSCSES) is a Python module that implements a one-dimensional Poisson-Boltzmann solver, used for modelling space charge properties in solid materials. 
In polycrystalline solid materials, grain boundaries and interfaces exist separating different crystalline domains. The structural distortion at these interfaces causes segregation of charge carriers to, or away from the grain boundary core. Due to this, the grain boundary core carries a net charge which causes the depletion or accumulation of charge carriers in the regions adjacent, known as space charge regions. Due to the variation on charge carrier concentrations, the ionic conductivity of the material can be strongly affected by the presence of grain boundaries.

### lattice_mc

[lattice_mc](https://github.com/bjmorgan/lattice_mc) is Python module for performing (kinetic) lattice-gas Monte Carlo (LGMC) simulations of ionic transport in solid electrolytes.

In solid electrolytes, ionic motion is typically effected by a series of discrete “jumps” where ions move between adjacent lattice sites. For dilute mobile ions, ionic trajectories are random walks, and simple analytical expressions exits that relate macroscopic transport coefficients, i.e. diffusion coefficients and ionic conductivities, to the microscopic jump frequency of individual ions. Practical solid electrolytes have high mobile ion concentrations, with significant interparticle interactions producing deviations from the dilute limit random walk behaviour. In general, the quantitative effect of interparticle interactions cannot be determined analytically. As an alternative, numerical simulations, such as lattice-gas Monte Carlo methods, can be used to directly calculate these relationships. Lattice-gas Monte Carlo methods are particularly suited to studying how varying properties across broad classes of materials give quantitative differences in macroscopic ionic transport, and can be used to understand the different transport properties of materials with, for example, different crystal structures or mobile ion stoichiometries.

### crystal_torture

[crystal_torture]https://github.com/connorourke/crystal_torture is a Python, Fortran and OpenMP crystal structure analysis module. The module contains a set of classes that enable:

- a crystal structure to be converted into a graph for network analysis
- connected clusters of crystal sites (nodes) to be retrieved and output
- periodicity of connected clusters of crystal sites to be determined
- relative path tortuosity to traverse a crystal within a connected cluster to be calculated for each site
