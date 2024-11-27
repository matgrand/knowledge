# Nonlinear MHD
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory.png)
# Why nonlinearity is difficult
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-1.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-2.png)
## What is and why we need a nonlinear exploration of the MHD model for plasmas
- MHD describes the macroscopic behaviour of electrically conducting fluids, i.e. a plasma; 
- Since the first studies in the 1950s, equilibrium and stability have been widely tackled: 
	- equilibrium state is separated from small perturbations, linear MHD;
### Linear / Quasi-linear / nonlinear approaches
- Linear picture: instability would lead to the destruction of the equilibrium configuration and loss of the plasma confinement.  
- Linear dynamics is a very important tool, but it is insufficient to predict the final state of unstable dynamics in various types of disrupted processes routinely observed in magnetically confined fusion plasmas 
- $\rightarrow$ necessity to consider nonlinear dynamics 
- Plasma discharges in reality exist even if instabilities are present $\rightarrow$ need to compute nonlinear behaviour or, at least, saturation levels. 
- The most privileged approach would be to follow the nonlinear development from an unstable equilibrium;
- POSSIBLE APPROACHES: 
	- study slowly evolving equilibrium states (ideal kink mode, resistive kink, asymptotic states of system relaxed under some constraints); 
	- Fully developed MHD turbulence (averages); 
	- numerical computations: problem is considered solved if “scaling laws” can be obtained. 
- But also QUASI-LINEAR theory: only take into account the action of the unstable modes on the equilibrium profiles.
## Diagram of possible plasma models
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-3.png)
- kinetic $\rightarrow$ very hard, there exists some gyro-kinetic  codes recently
- 2 fluid, first simplification
- 1 fluid $\rightarrow$ MHD
- next simplification $\rightarrow$ remove resistivity
## 3D nonlinear MHD equations
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-4.png)
- for example energy has nonlinearities: $\textbf{v} * \nabla p$   
- note: missing viscous term
## Model equations: fundamental time scales
- by studying the linearized small-amplitude oscillatory solution of the MHD model (theory of MHD waves, it would require a lesson on its own) the fundamental temporal and velocity scales emerge:
 $$
\text{Alfvén velocity} \quad v_a = \frac{B_0}{\sqrt{\mu_0\rho_0}}
$$
and, by assuming a macroscopic length of the system L one gets the Alfvén time $\tau_a =  L / v_a \approx 10^{-7}$
- By rewriting the equations of slide 6 normalizing all quantities to the Alfvén velocity and time and to the macroscopic length one can obtain the resistive time scale $\tau_R = \frac{\mu_0 L^2}{\eta} \approx 10^{0} - 10^{-1}$
# Resistive MHD
## Basics 
### Timescales involved
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-5.png)
- Lundquist number implies non-linear resistive MHD
### Remind of Spitzer's formula for the resistivity of a plasma
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-6.png)
- collisions are electromagnetic collisions $\rightarrow$ small deflections $\rightarrow$ resistivity
- note: confined plasma is **not** isotropic $\rightarrow$ ie. viscosity is stronger along perperndicular direction 
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-20241126145420367.jpg)
## Ideal vs resistive MHD
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-7.png)
- left: no resistivity, right: non-zero resistivity
- magnetic islands are consequences of instabilities
## Free energies to drive MHD modes / instabilities
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-8.png)
1) Magnetic reconnection / resistive-kink tearing modes dynamics in resistive MHD
2) Sawtoothing in tokamaks / nonlinear cycles
# Magnetic reconnection
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-9.png)
- Magnetic reconnection is a ***change of connections of magnetic field lines*** in highly conducting plasmas. A modification of the magnetic field topology results(1) . 
- Magnetic reconnection is a common phenomenon in space and laboratory plasmas: it is found in solar flares(2) , jets from active galactic nuclei(3) strongly magnetized neutron stars(4) astrophysical dynamos(5) large-scale magnetic self-organization of toroidal plasmas for magnetic fusion experiments(6) . 
- A common signature of ***magnetic reconnection is the release of magnetic energy, converted into kinetic and thermal internal energy of the plasma***, and observed as acceleration of particles to non-thermal velocities, and as generation of waves and turbulence. Another signature of reconnection is the presence of so-called current sheets. 
- In toroidal experiments for magnetic confinement of fusion plasmas, reconnection is generally linked to the ***opening of “islands”*** in the field lines topology. For optimum confinement magnetic field lines should lie on nested magnetic flux surfaces (which means existence of a function 𝜒 such that 𝑩 ⋅ 𝛻𝜒 = 0, with the shape of a topological torus). 
- However, such magnetic fields can be ***unstable*** in the vicinity of the regions where field lines close on themselves, and a transverse component of the magnetic field opens the magnetic islands, bounded by a so-called separatrix containing a region with “X” topology.
## Reconnection $\rightarrow$ Sweet - Parker model
Basic picture: two magnetic field lines being carried by the fluid come closer together and by the action of resistivity they are cut and reconnected in a different topology
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-12.png)
- opposite directions top/bot
- x is in the top direction (idiot)
- ideal = zero-resistivity
- continuity eq $\rightarrow$ what comes from top/bot needs to exit from the sides
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-13.png)
- note: last eq is an extreme semplification: curl is even a spatial derivative
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-14.png)
- follow video for explanation of every step
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-15.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-16.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-17.png)
- Assume it to be Alfven velocity, no real reason, wtf
- This was an excercise in dimensional analysis and very specific MHD problem, what they did in the 50s wihtout computers
- This was the first prediction of the reconnection rate, they found out that the rate is within the range of MHD, therefore it could be studied with MHD.
- $S^{-1/2} \approx 10^{-3}$
- But in reality reconnection can be much faster
### The issue of "fast reconnection"
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-18.png)
- not fully clear today
- they thought it would require 3D geometry, but it's only approachable recently
## Magnetic islands: naive
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-19.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-20.png)
Visualizing the last equation using contourplot
### Half width $\textbf{w}$
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-21.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-22.png)
- similar to a state space of a pendulum
- width of the magnetic island is proportional to sqrt of B
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-23.png)
- k = 3
- creates X-points
- remember left and right field have opposite direction
## Magnetic reconnection can happen in a tokamak
- This can happen when the safety factor is rational
- check Zohn book about MHD stability
- the huge simplification of Sweet-Parker model is actually very common in tokamak -> very relevant
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-24.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-25.png)
- Rutherford: magnetic island growth stops at a certain point
## Nonlinear evolution:  Rutherford equation
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-26.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-27.png)
- law for the dynamics of the width of the island
- not from first principles, phenomenological law
- many laws in plasma physics are ***not*** from first principles
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-28.png)
- bootstrap current
- big eq is a modern version of Rutherford eq, still has linear term
### More advanced models
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-29.png)
- not a beautiful eq
### From the 80s: numerical solutions
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-30.png)
low $\beta$ in reality: mag pressure >> kinetic pressure
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-31.png)
video:
- the perturbation flatten the current profile
- after the current gradient gets flattened the job of the island is done and stops growing
### Effect on kinetic profiles
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-32.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-33.png)
- contour plot of the temperature
- constant inside the mag island: very bad
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-34.png)![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-35.png)
# RFP 
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-36.png)
the island becomes so big it becomes the equilibrium
# Sawtooth instability
## Reminder: linear theory of internal kink modes
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-37.png)
- $\rightarrow$ current cannot exceed a certain value (disruption): hard limit
- another hard limit is Troyon limit
- and density limit (disruption), there is a max density proportional to the current $\rightarrow$ 2 limits on current
### Nonlinearity
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-38.png)
- picture from Zohn book
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-39.png)
- lower $q$ means high plasma current $\rightarrow$ source of instability
- (rewatch)
- example of mixed instability
- flattens $\rightarrow$ bad, we lose energy
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-40.png)
### Resistive internal kink: reconnection and island formation
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-41.png)
### Internal kink modes: nonlinear cycles
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-42.png)
### Nonlinear model to describe sawtoothing
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-43.png)
- $P$ is the external power
- pink term: nonlinear -> mix between predator and pray
### Solution to the microproblem
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-44.png)
- this problem is very recent, very hard
- not predictive power
- the current gradient grows until an instability kills it, instantly and periodically
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-45.png)
- $q = 1$ requirement for the instability
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-46.png)
- time in the order of 2 ms
- quiet fast, in the middle of ideal (e-6) and resistive (e0)
- sawtooth crash -> collapse in magnetic power
- below -> spectrum of the MHD modes
- multiple harmonics may be involved in the instability, interacting with each other, exchanging energy
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-47.png)
- plasma becomes unordered, caos theory
- probably harmonic resonance
### More info about sawtoothing
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-48.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-49.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-50.png)

# High Performance Computing (HPC)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-51.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-52.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-53.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-54.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-55.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-56.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-57.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-58.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-59.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-60.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-61.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-62.png)
![](imgs/L3%20-%20M.%20Veranda%20-%20Nonlinear%20magnetohydrodynamics%20theory-63.png)
- marco.veranda@igi.cnr.it