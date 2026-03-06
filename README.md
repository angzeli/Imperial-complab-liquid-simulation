# 🧪 Liquid Simulation — Computational Lab

This repository contains materials for a computational chemistry lab focused on **molecular dynamics (MD) simulations of simple liquids** using the **Lennard–Jones (LJ) potential**.

The project explores the theoretical foundations of MD simulations as well as the analysis of structural and dynamical properties of simulated systems.

Topics covered include:

- Molecular dynamics simulation methodology
- Verlet and Velocity-Verlet integration algorithms
- Periodic boundary conditions
- Lennard–Jones interaction potential
- Structural properties of liquids
- Radial distribution functions
- Diffusion and dynamical behaviour of particles

The repository also contains Python scripts used for data analysis and visualisation, along with the final report written in LaTeX.

---

## 📂 Repository Structure
```python
├── data/              # Raw simulation outputs and processed datasets
├── python_plot/       # Python scripts for data analysis and visualisation
├── reports/           # LaTeX source and compiled PDF reports
├── LICENSE            # Project license
└── README.md          # Repository documentation
```

### `data`
Contains simulation outputs and numerical data generated during the molecular dynamics runs. These may include trajectories, thermodynamic quantities, and derived datasets used for analysis.

### `python_plot`
Python scripts used to process and visualise simulation data. These scripts generate plots such as:

- Lennard–Jones potential curves
- radial distribution functions
- time-dependent simulation properties

The scripts rely primarily on:

- `numpy`
- `matplotlib`

### `reports`
Contains the written report for the computational lab, including:

- theoretical derivations
- simulation analysis
- figures and visualisations
- discussion of results

Reports are written in **LaTeX**.

---

## 🔬 Scientific Background

Molecular dynamics simulations provide a computational approach for studying the behaviour of many-particle systems by integrating **Newton’s equations of motion**. In this lab, particle interactions are modelled using the **Lennard–Jones potential**, which captures short-range Pauli repulsion and long-range London dispersion interactions.

The simulations allow investigation of:

- equilibrium properties of condensed phases
- structural ordering in liquids
- dynamical behaviour such as diffusion

---

## ⚙️   Requirements

Python environment:
```python
numpy
matplotlib
```
LaTeX (for compiling the report).

---

## 👤 Author

**Angze Li**  
MSci Chemistry  
Department of Chemistry  
Imperial College London

---

## 📜 License

This project is distributed under the terms specified in the `LICENSE` file.

