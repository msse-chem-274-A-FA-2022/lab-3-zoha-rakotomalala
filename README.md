# CHEM 274A - Lab 3
September 27, 2022

Today, we will be focusing on learning about basic quantum mechanics calculations using the [Psi4 Quantum Chemistry package](https://psicode.org/). This lab uses Python, matplotlib, numpy, and the `psi4` library.

## Objectives
- Analyze and optimize the geometry of a molecule using PsiAPI
- Plot bond length and energy changes during an optimization
- Define dihedral angles for intramolecular coordinates
- Use loops
- Scan and plot 2D and 3D models of potential energy surfaces (PES) for the interaction between two molecules

## Setup
1. Clone this repo!
2. Create a `conda` environment using the provided `conda-env.yaml` file. We recommend using the `mamba` package manager to create this environment

```bash
conda install mamba
mamba env create -f conda-env.yaml
```

3. This will install PsiAPI in an environment called `qm-tools`. You can activate the `qm-tools` by doing

```bash
conda activate qm-tools
```

## Exercise
Use the notebook `qm_lab3_geometry_optimization.ipynb` to explore Geometry Optimization. Follow the instructions in the notebook.
Use the notebook `qm_lab3_intramolecular.ipynb` to explore Intramolecular Potential Energy Surfaces. Follow the instructions in the notebook.
Use the notebook `qm_lab3_intermolecular.ipynb` to explore Intermolecular Potential Energy Surfaces. Follow the instructions in the notebook.