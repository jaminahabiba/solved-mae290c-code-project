Download Link: https://assignmentchef.com/product/solved-mae290c-code-project
<br>
Building on homework modules 1 and 2, write a spectral code to simulate 2D turbulence in a 1536 × 1536 square periodic box. Start with the 2D Navier-Stokes equations in streamfuncion / vorticity formulation and discretize them spatially using a Fourier spectral method. Use your favorite dealiasing scheme (e.g. 2<em>/</em>3 rule would use 1024×1024 Fourier modes) and a third-order, low storage, semi-implicit Runge-Kutta method to integrate in time. Solve these equations for a Reynolds number

<em>,</em>

where <em>L </em>is the size of the box, <em>ν </em>is the kinematic viscosity and <em>u</em><sup>0 </sup>is the root mean square of the velocity fluctuations at <em>t </em>= 0. Set a random initial condition with energy spectrum

<em>.</em>

Run this simulation and

<ol>

 <li>Estimate the transient time that is required for the random initial conditions to transform into a sea of compact vortices.</li>

 <li>Plot the time evolution of the total enstrophy and energy in the box. Which one decaysfaster? Why?</li>

 <li>Plot 2D vorticity fields for the instants of time when the energy is 90%, 80%, 70%,60% and 50% of its initial value. Describe qualitatively the evolution of vortex number and size.</li>

</ol>