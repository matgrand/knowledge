# Modelling of RFX-mod2 tokamak equilibria with DEMO-like shape conditions and negative triangularity #paper

![](imgs/rfx_mod2_equilibria_demo_shape_negative.png)

- They used 2 interesting numerical tools:
	- **Inverse Equilibrium Tool ([IET](../phd/IET.md))**: it's a tool to calculate the coils currents needed to obtain a predetermined plasma shape, with well defined total plasma current #plasma_current, total poloidal magnetic flux at the boundary #poloidal_magnetic_flux and plasma current density profile #plasma_current_density.
	- **[CREATE-L](../phd/CREATE-L.md)** is a simple+reliable linearized plasma response model, used to control plasma current #plasma_current, position #plasma_position, and shape #plasma_shape
- They tested some DEMO-like shapes in RFX-mod2 
- to have an initial validation of the control scheme they used CREATE-L code, which is an alternative code to IET basically, but also outputs a MIMO state space model for modeling plasma behavior around an equilibrium point/time instant. 
  This allows to understand plasma vertical instability growth rate, and design appropriate controllers.
  > The removal of the vessel in the mod2 revision is negligible.
## Key takeaways
- there exists multiple useful codes for plasma equilibria
- rfx-mod2 is a flexible machine, for both tokamak and rfp configurations
- they show how it's important to design a new controller 
	- [ ] design a controller for this shapes