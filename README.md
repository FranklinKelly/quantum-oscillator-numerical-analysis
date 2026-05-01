## Purpose

This repository numerically solves the Schrodinger equation, finding the eigenvalues and eigenfunctions of the Hamiltonian: $$H_0 = \frac{p^2}{2m} + \frac{1}{2}m\omega^2 x^2$$ for $n=0,1,2$. It also solves the problem with $$H_1 = \frac{p^2}{2m} + \frac{1}{2}m\omega^2 x^2 + \alpha x^3$$
We compare the first numerical solutions to the analytical solutions for $H_0$. 

## Setup

Install [python3](https://www.python.org/downloads/)

to set up dependencies, run:
```bash
pip install scipy matplotlib numpy jupyter
```


To start the notebook, now run:
```bash
jupyter lab
```

