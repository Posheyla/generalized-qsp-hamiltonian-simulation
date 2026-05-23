# Generalized Quantum Signal Processing for Hamiltonian Simulation

This project explores the implementation and analysis of **Generalized Quantum Signal Processing (GQSP)** methods for Hamiltonian simulation and polynomial transformations of unitary operators using **Qiskit**.

---

## Overview

Generalized Quantum Signal Processing extends traditional Quantum Signal Processing (QSP) by enabling more flexible polynomial transformations of quantum operators through arbitrary SU(2) rotations.

In this project, we implemented and analyzed GQSP techniques for:

- Hamiltonian simulation
- Polynomial approximation
- Angle synthesis and optimization
- Validation and reconstruction accuracy
- Molecular-system simulations
- Quantum chemistry-inspired applications

The work investigates how the accuracy of GQSP simulations varies with the polynomial degree and applies the framework to the **H₃ molecular reaction model**.

---

## Methods

The implementation pipeline includes:

### 1. Complementary Polynomial Construction
- Computation of the companion polynomial \(Q(z)\)
- Fejér–Riesz decomposition
- Polynomial feasibility validation

### 2. Rotation Angle Synthesis
- Inverse recurrence factorization
- SU(2) polynomial decomposition
- Angle extraction for GQSP circuits

### 3. Validation and Error Analysis
- Reconstruction accuracy verification
- Numerical error analysis
- Unitarity validation
- Comparison between target operators and GQSP outputs

### 4. Hamiltonian Simulation
- Time evolution simulation using polynomial approximations
- Molecular-system analysis for the H₃ reaction model
- Population transfer dynamics under different geometries

---

## Applications

This project explores Hamiltonian simulation in the context of molecular dynamics and quantum chemistry.

The implementation includes:
- Potential energy surface visualization for the H₃ system
- Equilibrium and non-equilibrium molecular configurations
- Time-evolution analysis under varying polynomial orders
- Accuracy comparison between exact and GQSP-approximated dynamics

---

## Technologies Used

- Python
- Qiskit
- NumPy
- SciPy
- Matplotlib
- Quantum Algorithms
- Hamiltonian Simulation

---

## Repository Structure

```txt
/notebooks   -> Qiskit implementations and experiments
/report      -> Final project paper
/slides      -> Presentation materials
/images      -> Figures, plots, and visualizations
```

---

## Results

The implementation successfully demonstrated:

- Accurate polynomial reconstruction
- Stable angle synthesis
- Low numerical reconstruction error
- Quantum operator approximation using GQSP methods
- Improved simulation accuracy with increasing polynomial degree

The project also analyzed the computational complexity of classical angle synthesis methods and evaluated the scalability of GQSP for molecular simulation tasks.

---

## Key Visualizations

- H₃ potential energy surfaces
- GQSP reconstruction accuracy analysis
- Population transfer dynamics
- Polynomial approximation validation
- Time-evolution simulations

---

## References

1. Motlagh & Wiebe, *Generalized Quantum Signal Processing*, PRX Quantum (2024)

2. Low & Chuang, *Hamiltonian Simulation by Qubitization*, Quantum (2019)

3. Childs & Wiebe, *Hamiltonian Simulation Using Linear Combinations of Unitaries* (2012)

---

## Academic Context

This project was developed as part of graduate coursework at:

**North Carolina State University (NC State)**  
Department of Electrical and Computer Engineering

### Team Members
- Kevin J. Joven
- Luisa Chavez
- Piyush Saini

### Faculty Advisor
- Dr. Sabre Kais

---
