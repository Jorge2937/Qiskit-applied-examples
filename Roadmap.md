# Roadmap

This document outlines the planned examples for this repository.
The roadmap is intentionally conservative to avoid over-scoping.

---

## First example: Bell states and noise effects

**Status:** Planned  
**Location:** basics/bell_states/

### Objectives
- Understand how entanglement is created using quantum circuits
- Implement Bell states using Qiskit
- Compare ideal simulations with noisy simulations
- Illustrate why noise is a critical limitation in current hardware

### Contents
- Construction of Bell states using basic gates
- Measurement statistics and visualization
- Ideal simulator results
- Noisy simulator results
- Comparison and discussion

### Deliverables
- `bell_states.ipynb`  
  Self-contained Jupyter notebook with code and inline explanations
- `explanation.md`  
  Conceptual explanation and interpretation of results
- Simple plots comparing ideal vs noisy outcomes

### Out of scope
- Bell inequality violations
- Experimental loopholes
- Advanced noise mitigation techniques
- Large-scale entanglement

The purpose of this example is clarity and reproducibility, not completeness.

---

## Future examples (tentative)

These examples will only be started once the previous one is completed.

- Basic circuit execution on real IBM Quantum hardware (optional)
- Grover's search algorithm (toy problems)
- Variational Quantum Eigensolver (H₂ molecule)
- Simple QAOA example for combinatorial optimization
