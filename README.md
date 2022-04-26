# Particle distribution in scalar field

In this notebook we explain in detail the approach used in [1] to derive the particle distribution in a scalar field.

The particles follow a density profile $n(x)$, while the field is also a function of the coordinates $\phi(x)$. The problem is now to find the distribution $\mathrm{d}N/\mathrm{d}\phi (\phi)$. We show the consistency between 3 approaches: analytical, numerical integration and sampling.

The analytical approach requires inverting the relation between field and coordinate, writing the latter as a function of the former.
The numerical integration approach borrows from the Density of States concept in Condensed Matter physics.
The sampling approach consists on generating random coordinates of the particles, calculating the local field values for each of these, and build a histogram from it.

References:
[1] Amaro O., Vranic M., "Optimal laser focusing for positron production in laser-electron scattering" pre-print https://arxiv.org/abs/2106.01877 , journal https://iopscience.iop.org/article/10.1088/1367-2630/ac2e83
