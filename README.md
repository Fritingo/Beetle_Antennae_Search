# Beetle Antennae Search (BAS) Visualization

This repository provides a Python-based visualization of the Beetle Antennae Search (BAS) algorithm, a novel metaheuristic optimization algorithm inspired by the foraging behavior of beetles.

## Description

The script `BAS_2D.py` implements a 2D visualization of the BAS algorithm. The beetle explores a 2D space to find the optimal solution (goal), and its path is plotted in real-time. The fitness of the beetle's position is determined by its proximity to the goal.

For more information on the BAS algorithm, refer to the original paper: [Beetle Antennae Search Algorithm](https://arxiv.org/abs/1710.10724).

![BAS Visualization](https://raw.githubusercontent.com/Fritingo/Beetle_Antennae_Search/master/doc/BAS.gif)

## Requirements

- Python 3
- NumPy
- Matplotlib
- SciPy

## Usage

To run the visualization, execute the following command in your terminal:

```bash
python BAS_2D.py
```

The script will generate a plot showing the beetle's path as it searches for the goal. The simulation will continue until the beetle's fitness reaches a certain threshold.
