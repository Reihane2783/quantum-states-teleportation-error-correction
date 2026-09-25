# Quantum States, Teleportation, and Error Correction

A Qiskit-based quantum computing project exploring fundamental concepts in quantum information through quantum circuit simulation and statevector analysis.

## Overview

This project demonstrates:

- Preparation and verification of the four Bell states
- Quantum statevector analysis
- Quantum teleportation
- Bloch sphere visualization
- Three-qubit phase-flip error correction
- Syndrome extraction and conditional correction
- Numerical verification of state recovery

## Contents

### Bell States

Construction and statevector verification of the four Bell states:

- $|\Phi^+\rangle$
- $|\Phi^-\rangle$
- $|\Psi^+\rangle$
- $|\Psi^-\rangle$

### Quantum Teleportation

Implementation of the quantum teleportation protocol for the $|+\rangle$ state.

The circuit uses:

- A shared Bell pair
- Alice's measurements
- Classical measurement results
- Bob's conditional corrections

The resulting state is verified using the statevector and Bloch sphere.

### Phase-Flip Error Correction

Implementation of a three-qubit error-correction scheme for a single phase-flip ($Z$) error.

The circuit includes:

1. Arbitrary input-state preparation
2. Logical-state encoding
3. Single-qubit phase-flip error
4. Syndrome extraction
5. Conditional error correction
6. Ancilla reset
7. Logical-state decoding
8. State recovery verification

## Technologies

- Python
- Qiskit
- Qiskit Aer
- NumPy
- Matplotlib
- Jupyter Notebook

## Repository Structure

```text
quantum-states-teleportation-error-correction/
│
├── README.md
└── quantum_states_teleportation_error_correction.ipynb
