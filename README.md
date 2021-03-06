# Jellymorph
Modelling the geometry and dynamics of self-propelling jellies

## Objective
- auto-generate coordinate information & triangulation connectivity on surfaces in 3D space
- construct surfaces from cross-sectional contours of 3D shapes at various depths (slices) and directions
- optimise surface discretization for equiangular triangulation
- option for regularly structured or unstructured triangulation
- enable generation of multiple discretization patterns per surface geometry
- enable attribute encoding on sub-elements

## Motivation
- rapid generation of discretized surfaces as input for Surface Evolver [1-4]
- simple graphical user interface for designing smooth 3D shapes/surfaces

## Applications
- geometry file for 3D printing
- model physics of mechanical walkers [5-7]
- model locomotion of 3D cellular automata induced by self-contractility
- understand non-equilibrium physics underlying cell shape dynamics & motility
- abstract data representation & computation [8,9]

## Future goals
- efficient auto-refinement/coarsening of triangulation
- field projection over triangulation [10,11]
- mesh-free shape boundary

## References
1. http://facstaff.susqu.edu/brakke/evolver/evolver.html
2. http://facstaff.susqu.edu/brakke/aux/physicsofmicrodroplets/all.html
3. http://facstaff.susqu.edu/brakke/aux/openmicrofluidics/default.html
4. http://facstaff.susqu.edu/brakke/evolver/workshop/
5. http://boim.com/Walkin8r/JansenCycle.gif
6. https://www.wikiwand.com/en/Jansen%27s_linkage
7. https://youtu.be/Z1xvAZve9aE *by Yuanming Hu*
8. https://arxiv.org/abs/2006.02870
9. https://arxiv.org/abs/1601.01704
10. http://geometry.caltech.edu/pubs/dGDT16.pdf
11. https://dl.acm.org/doi/10.1145/3386569.3392389
