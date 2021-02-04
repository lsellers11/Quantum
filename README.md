# Quantum
Numerical simulations of quantum many-body systems.

Project Descriptions:

1. esandnucinabox.ipynb

  Self-consistent Hartree fock orbital eigen-solver for general number of electrons in a box with a randomized ion distribution with variable atomic number. Electron clustering at the perimeter is observed, as well as positive correlation between temperature and ion charge.
  
2. ev2asym3.ipynb

  Finite elementation of Hilbert space of 2 electrons in 1 physical dimension. We use slater dterminants as the finite elements so that the resulting wavefunctions are anti-symmetric, describing fermions. This version does not scale to higher particle numbers
  
3. antisymND.ipynb

  The higher dimension generalizatoin of [2], finite elementation of Hilbert space of N electrons in 1 physical dimension. We use slater determinants as the finite elements so that the resulting wavefunctions are anti-symmetric, describing fermions. Next steps involve expanding the number of physical dimensions, which entails encoding higher dimensional surfaces in the edges of the N-D cubes of the 1 physical dimension Hilbert space. 
