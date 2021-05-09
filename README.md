# Hillas Plot

Showing upper limits on the reachable cosmic ray energy dependent on the size of the acceleration region and the magnetic field strength.

# Technical

Notebook used for plotting.

Data is read from two yaml files.

[HillasObjects.yaml](HillasObjects.yaml):
List of objects to be plotted. Given is object type (Marker, Rectangle, Trapezoid), coordinates, and labels. Setting labels needs a bit of fine tuning.

[ParticleAcceleration.yaml](ParticleAcceleration.yaml):
List of lines to be drawn for maximal achievable energy using the Hillas formula:
```math
B_{\mu G}L_{pc}>2E_{15}/Z\beta
```

# References

1. Hillas, M. [Ann. Rev. Astron. Astrophys. 1984 22:425](https://doi.org/10.1146/annurev.aa.22.090184.002233)
2. Artsen, M.G., et al, Advances in Space Research, Volume 62, Issue 10, p. 2902-2930; [arXiv:1701.03731](https://arxiv.org/abs/1701.03731) (Figure 1)
3. Alves Batista, R., Biteau, J., Bustamante, M., et al., 2019, Frontiers in Astronomy and Space Sciences, 6, 23. [arXiv:1903.06714](https://arxiv.org/abs/1903.06714) (Figure 11)
