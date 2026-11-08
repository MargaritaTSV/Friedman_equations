# Differential Equations in Astronomy: the Friedmann Equations

A Jupyter notebook that derives the Friedmann equations, solves them analytically and numerically, and uses them to model the expansion of the Universe.

## Requirements
Python 3 with `numpy`, `scipy`, `matplotlib`, and `jupyter`.

## Running
```bash
jupyter notebook Friedmann_equations.ipynb
```
Run all cells from top to bottom. 

## Data
- Galaxy distances are Cepheid distances to supernova host galaxies from the SH0ES programme (Riess et al. 2022, *ApJL* 934, L7).
-  Recession velocities are CMB-frame redshifts corrected for peculiar velocities, from the Pantheon+SH0ES data release (Scolnic et al. 2022, *ApJ* 938, 113; Brout et al. 2022, *ApJ* 938, 110).
- Cosmological parameters are from Planck 2015 (Planck Collaboration 2016, *A&A* 594, A13).
