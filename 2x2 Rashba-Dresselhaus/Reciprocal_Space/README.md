# 2x2 Rasbha-Dresselhaus Quantum Solver in Real space

* This repository contains 2 libraries to solve a system (in the example, a coupled quantum well) with Rashba and Dresselhaus spin-orbit interactions for the conduction band solved in reciprocal space.

* With it you can, for example, find the Envelope Functions for n-state with spin Up and Down. The method give you Wave function in reciprocal space, but, with a Fourier Transform you can obtain it in real space.

<p align="center">
  <img width="700" height="400" src="WF_Example.jpg">

* Or find the dispersion E-k for a specific in-plane direction.
  
<p align="center">
  <img width="400" height="400" src="Dispersion_Example.jpg">
</p>
  
* For the solution it is necessary to have the potential profile in the reciprocal space, for this it is essential to have a good approximation in the reciprocal space of it.

<p align="center">
  <img width="700" height="400" src="Conduction_Band_Transform_Example.jpg">
</p>

* For more details check Example Notebook.
