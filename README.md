Optimal laser focusing for positron production in laser–electron scattering
=============================================================================================================================



<a href="https://iopscience.iop.org/article/10.1088/1367-2630/ac2e83" style='vertical-align:middle; display:inline;'><img
							src="https://img.shields.io/badge/NJP-OptimalFocusing-blue.svg" class="plain" style="height:25px;" /></a>
<a href="https://arxiv.org/abs/2106.01877" style='vertical-align:middle; display:inline;'><img
							src="https://img.shields.io/badge/plasm--ph-arXiv%3A2106.01877-B31B1B.svg" class="plain" style="height:25px;" /></a>


Authors:  Óscar Amaro and Marija Vranic

Abstract: _Laser–electron beam collisions that aim to generate electron–positron pairs require laser intensities I ≳ 1021 W cm−2, which can be obtained by focusing a 1-PW optical laser to a spot smaller than 10 μm. Spatial synchronization is a challenge because of the Poynting instability that can be a concern both for the interacting electron beam (if laser-generated) and the scattering laser. One strategy to overcome this problem is to use an electron beam coming from an accelerator (e.g., the planned E-320 experiment at FACET-II). Even using a stable accelerator beam, the plane wave approximation is too simplistic to describe the laser–electron scattering. This work extends analytical scaling laws for pair production, previously derived for the case of a plane wave and a short electron beam. We consider a focused laser beam colliding with electron beams of different shapes and sizes. The results take the spatial and temporal synchronization of the interaction into account, can be extended to arbitrary beam shapes, and prescribe the optimization strategies for near-future experiments._

Paper in New Journal of Physics: https://iopscience.iop.org/article/10.1088/1367-2630/ac2e83

### Particle distribution in scalar field

In this notebook we explain in detail the approach used in [1] to derive the particle distribution in a scalar field.

The particles follow a density profile $n(x)$, while the field is also a function of the coordinates $\phi(x)$. The problem is now to find the distribution $\mathrm{d}N/\mathrm{d}\phi (\phi)$. We show the consistency between 3 approaches: analytical, numerical integration and sampling.

The analytical approach requires inverting the relation between field and coordinate, writing the latter as a function of the former.
The numerical integration approach borrows from the Density of States concept in Condensed Matter physics.
The sampling approach consists on generating random coordinates of the particles, calculating the local field values for each of these, and build a histogram from it.

References:
[1] Amaro O., Vranic M., "Optimal laser focusing for positron production in laser-electron scattering" pre-print https://arxiv.org/abs/2106.01877 , journal https://iopscience.iop.org/article/10.1088/1367-2630/ac2e83


Related repositories
----------------------
- Blackburn et al 2017 PRA https://github.com/RePlasma/PhysRevA_96_022128
- Vranic et al 2019 PoP https://github.com/RePlasma/1.5090992
- A Mercuri-Baron et al 2021 NJP https://github.com/RePlasma/New_J._Phys._23_085006
- Golub et al 2022 PRD https://github.com/RePlasma/PhysRevD.105.116016
- Amaro et al 2024 PPCF https://github.com/OsAmaro/QScatter
