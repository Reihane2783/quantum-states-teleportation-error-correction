# Quantum States, Teleportation, and Error Correction

A Qiskit-based quantum computing project demonstrating Bell states, quantum teleportation, and phase-flip error correction using quantum circuit simulation and statevector analysis.

## Overview

This project explores fundamental concepts in quantum information using **Qiskit**.

The notebook includes:

- Preparation and analysis of the four Bell states
- Quantum statevector representation
- Quantum teleportation protocol
- Bloch sphere visualization
- Three-qubit phase-flip error correction
- Syndrome extraction and conditional correction
- Numerical verification of recovered quantum states

## Contents

### 1. Bell States

The four maximally entangled Bell states are constructed and verified:

\[
|\Phi^+\rangle =
\frac{1}{\sqrt{2}}(|00\rangle+|11\rangle)
\]

\[
|\Phi^-\rangle =
\frac{1}{\sqrt{2}}(|00\rangle-|11\rangle)
\]

\[
|\Psi^+\rangle =
\frac{1}{\sqrt{2}}(|01\rangle+|10\rangle)
\]

\[
|\Psi^-\rangle =
\frac{1}{\sqrt{2}}(|01\rangle-|10\rangle)
\]

The generated states are analyzed using Qiskit's `Statevector` representation.

---

## 2. Quantum Teleportation

The notebook implements the standard quantum teleportation protocol.

An input state:

\[
|+\rangle =
\frac{1}{\sqrt{2}}(|0\rangle+|1\rangle)
\]

is transferred from Alice's qubit to Bob's qubit using:

- A shared Bell pair
- Alice's Bell-basis measurement
- Classical measurement results
- Bob's conditional quantum corrections

The final state is verified using:

- Statevector analysis
- Bloch sphere visualization

---

## 3. Phase-Flip Error Correction

A three-qubit quantum error correction scheme is implemented to correct a single phase-flip error.

The workflow includes:

1. Preparation of an arbitrary input quantum state
2. Encoding into three physical qubits
3. Introduction of a single Pauli-Z error
4. Syndrome extraction using ancilla qubits
5. Identification of the corrupted qubit
6. Conditional quantum correction
7. Decoding of the logical qubit
8. Comparison between initial and recovered states

The final recovery is evaluated using statevector overlap.

---

## Technologies

- Python
- Qiskit
- Qiskit Aer
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Installation

Clone this repository:

```bash
git clone https://github.com/YOUR_USERNAME/quantum-states-teleportation-error-correction.git
