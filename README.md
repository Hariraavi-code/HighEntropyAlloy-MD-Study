# High-Entropy Alloy Molecular Dynamics Study

A computational study to understand the influence of temperature and strain rate on the mechanical behavior of a five-component equiatomic high-entropy alloy (HEA), conducted using molecular dynamics (MD) simulations in LAMMPS.

## Project Overview

This project simulates tensile and compressive behavior of HEAs under various conditions to uncover atomic-scale deformation mechanisms. The study focuses on strain rate sensitivity, thermal softening, and structural evolution using radial distribution functions (RDF).

## Key Features

- Simulated using **LAMMPS** with **EAM potentials**
- Covered **temperature range**: 100K – 800K
- Covered **strain rates**: 0.001 – 0.05 ps⁻¹
- Visualized deformation using **OVITO**
- Analyzed both **tensile and compressive** loading
- Structural analysis via **Radial Distribution Function (RDF)**

## Methodology

- Built a 100 × 40 × 40 Å³ FCC lattice for the HEA
- Equilibrated system using Nose-Hoover thermostat (50 ps)
- Deformed system over 500 ps under uniaxial loading
- Sampled stress data every 100 fs
- Analyzed dislocation evolution and phase transformations

##  Key Observations

- **Tensile strength** drops significantly with temperature due to thermal softening.
- **Yield stress** is 18–22% higher in compression than in tension.
- **Strain rate sensitivity** is pronounced below 300K.
- **RDF analysis** shows crystalline-to-amorphous transformation during loading.
- **Critical strain threshold (~0.15 in tension, ~0.08 in compression)** remains consistent across conditions.

## Documentation

Full technical report and visual data are available in [`report.pdf`](report.pdf),['slides.pdf'](slides.pdf)

