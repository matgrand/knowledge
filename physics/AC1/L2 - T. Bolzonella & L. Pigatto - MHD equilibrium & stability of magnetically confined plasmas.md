# MHD equilibrium & stability of magnetically confined plasmas
- video about TCV: plasma sim done in Unity
## Scales of plasma physics
![](imgs/L2%20-%20Tommaso%20Bolzonella.png)
![](imgs/L2%20-%20Tommaso%20Bolzonella-1.png)
## Models for plasma description
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto.png)
- $10^{19} - 10^{20}$ particles for single particles
- in some cases resistance is playing a key role (dissipation)
# MHD model
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-1.png)
- assumes an external mag field
- (1) + (2) similar to Navier Stokes
- (2) vector eq (conservazione forze meccaniche)
- (3) can be written in different ways, scalar eq
- (1) (2) (3) mass momentum energy
- (4) -> electromagnetism (Maxwell)
- variables are not indipendent
### Assumptions
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-2.png)
- collisions leads the system to behave as a fluid
- these are coulomb collisions, very long range collisions, not head to head, difficult to model
### Remarks
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-3.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-4.png)
- $B$ (Mag field) is the only indipendent variable -> induction equation
- $B$ depends also on a diffusion term, it depends on how to the plasma moves inside
- The diffusion part generates the permanent mag field background in the universe
- diffusion part highly nonlinear
- for normal ideal fluids, vorticity is conserved; in this case vorticity is equivalent to resistivity
- in this approx mag field and plasma behave as a single entity
# Plasma equilibrium
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-5.png)
- we usually start from a static equil (no term depending on $v$)
### Equilibrium is balance between confining magnetic field and plasma pressure
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-6.png)
classic axial-symmetric equilibrium
# Static equilibrium for toroidal plasmas
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-7.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-8.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-9.png)
- change of basis
- $R_0$ can be either the machine center or the magnetic center (ask) -> ask the correct formal definition of poloidal and toroidal flux
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-10.png)
- $\Phi$ and $\Psi$ are the Toroidal and Poloidal fluxes
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-11.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-12.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-13.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-14.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-15.png)
the legendary $p'$ and $f'$ defined
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-16.png)
Grad-Shafranov equation
- for some ad hoc parameterizations of the profiles it's possible to solve them analytically
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-17.png)
### Remarks on equilibrium for toroidal plasmas
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-18.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-19.png)
- but how does one define the fucking profiles?
### Figures of merit: $q$ safety factor
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-20.png)
- note: integration over the flux lines
- value of safety factor has a direct link with stability properties of the eq
## Figures of merit: $\beta$ 
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-21.png)- different version of $\beta$: poloidal, toroidal, normalized wrt plasma current, averaged, averaged across profile
### The "Straight Tokamak" approx
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-22.png)
### Safety factor $q$ in straight tokamak approx
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-23.png)
- edge safety factor $q_a$
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-24.png)
## Model for current density profiles
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-25.png)
- large aspect ratio + circular cross section
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-26.png)
# Stability
## Linear Stability
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-27.png)
## Perturbed linearized momentum equation
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-28.png)
- $\Delta p_1$ perturbed pressure (?)
## Linearized MHD equations
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-29.png)
### Introducing plasma displacement
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-30.png)
## Using $\xi$ in the linearized equaitons leads to the force operator 
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-32.png)
- do the calculation yourself, useful to develop your own code
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-33.png)
- bending magnetic fields requires a force (string = mag field line -> waves propagate)
- green = stabilizing, red = destabilizing
- pressure gradients tend to naturally decay, keeping them requires force (unstable dynamics)
### Normal modes
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-34.png)
### Eigenvalues properties
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-35.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-36.png)
- interesting discussion
## Energy principle: insight on stability without solving the eigenvalue problem
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-37.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-38.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-39.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-40.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-41.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-42.png)
## Current driven kink for large aspect ratio with low $\beta$
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-45.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-46.png)
# Examples
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-47.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-48.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-49.png)
### Comments
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-50.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-51.png)
## Early kink
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-52.png)
# Global MHD instabilities
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-53.png)
### Troyon limit
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-54.png)
# The Advanced Tokamak  (AT) scenario for steady state operation
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-55.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-56.png)
end of lecture here
- sand-avalanches-like instabilities limit the steepness of pressure gradients
- regions with max steepness in density create a toroidal "bootstrap current"
- bootstrap current is good bc u need to sustain plasma current in steady state operation, and bootstrap current can provide a part of that
- but it creates external kink instabilities (?)
- instabilities can happen at very different scales in space:
  - global deformation(kink)
  - instabilities at meso scales (r of device - larmor radius) -> start point of transport model
# Bonus
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-57.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-58.png)
![](imgs/L2%20-%20T.%20Bolzonella%20&%20L.%20Pigatto-59.png)
