## Flow Equation for Quantum Control - PhD Position Interview

This repo contains code used to carry out the project 'Flow Equation for Quantum Control'.
There are three scripts, one for each part of the project, which are set up to reproduce the figures used in the writeup directly.

part_a focuses on identifying the adiabatic regime for the specific Hamiltonian we consider.
part_b considers the effect of including additional counterdiabatic driving terms in the Hamiltonian to ensure states evolve adiabatically even when not in the adiabatic regime.
In part_c we solve a system of flow equations for the coefficients of the Hamiltonian expanded in an effective 4D operator subspace, which are designed to
  decimate the gauge potential terms in the counterdriven $H_{CD}(t)$ and produce an effective $H_{FF}(t)$. $H_{FF}(t)$ is a workaround that reproduces the effects of counterdiabatic driving
  using only experimentally accessible couplings $J(t), g(t)$.
