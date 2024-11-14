# Plasma Physics
Everything I know about plasma physics, spoiler: not much yet.

## To learn
- [ ] get better of fast manipulation on formulas/equations
- [ ] get better at fast reading/understanding equations
- [ ] study fluid-dynamics
## Interesting Material
- https://www.sciencedirect.com/topics/engineering/fusion-plasmas
- [Fusion Wiki](https://wiki.fusion.ciemat.es/wiki/Main_Page)
- [video series about fusion](https://www.youtube.com/watch?v=yuNf9jv3Ulg)
- [iter physics basics](https://iopscience.iop.org/issue/0029-5515/47/6)


## Plasma equilibrium reconstruction
It's reconstructing the plasma equilibrium inside the vessel given a variety of inputs, usually the currents in the poloidal coils.
In the general case requires to solve the MHD equilibrium, more specifically the force balance equation. 
When there is the assumption of axisymmetry, the force balance equation reduces to the Grad-Shafranov equation #gse.   
Therefore, to perform fast reconstruction, one considers the axisymmetric case, in 2D, and needs to solve #gse .

- plasma equilibrium reconstruction is computationally slow
- there exists a ton of codes that do it, both for 3D and 2D

> source: https://wiki.fusion.ciemat.es/wiki/MHD_equilibrium

# Random facts
- It is impossible to reconstruct the internal current density profile with only external magnetic measures