# Diffusion2D-Python-Package

## Instructions for students

Please follow the instructions in [exercise_python_packaging_text.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/building-and-packaging/material/exercise_python_packaging_text.md).

The code used in this exercise is based on [Chapter 7 of the book "Learning Scientific Programming with Python"](https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/).

## Project description

Information about solver.py: This code solves the diffusion equation in 2D over a square domain which is at a certain temperature and a circular disc at the center which is at a higher temperature. This code solves the diffusion equation using the Finite Difference Method. The thermal diffusivity and initial conditions of the system can be changed by the user. The code produces four plots at various timepoints of the simulation. The diffusion process can be clearly observed in these plots.

## Installing the package

### Using pip3 to install from PyPI

```pip3 install --index-url https://test.pypi.org/project/ostertmsdiffusion2D```

### Required dependencies

Install NumPy and Matplotlib with ```pip```.

## Running this package

Run the code using

```python
from ostertmsdiffusion2d import ostertmsdiffusion2d
ostertmsdiffusion2d.solve()
```

and observe the output. You should see four plots combined into one figure. Save this figure on your system.

## Citing

Authors:

- @IshaanDesai: the template
- @magnusostertag: the exercise
