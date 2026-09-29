# Two-Dimensional Ising Model

[Versión en español](README.md)

A Statistical Mechanics computational project studying two-dimensional Ising lattices with the Metropolis algorithm.

## Contents

The notebook simulates square and hexagonal lattices with periodic boundary conditions. It calculates and analyzes thermodynamic observables, including energy, magnetization, magnetic susceptibility, and specific heat, as functions of temperature and lattice size. It also explores thermalization and spin-state behavior at different temperatures.

The implementation and visualizations are in [`modelo_ising_2d.ipynb`](modelo_ising_2d.ipynb).

## Requirements

- Python 3
- NumPy
- Matplotlib
- Numba
- SciPy
- tqdm

## Running the notebook

Install the dependencies:

```bash
python -m pip install -r requirements.txt
```

Open `modelo_ising_2d.ipynb` in Jupyter or Google Colab and run the cells in order. Some simulations use large lattices and many iterations, so they may require significant time and memory.

## Team

Group 15, Statistical Mechanics, 2025 (second semester).

- *Sammy Vallejo*
- Eugenio Andrés Della Valle
- Abraham Machicado
