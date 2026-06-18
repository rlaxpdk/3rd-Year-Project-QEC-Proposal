# Quantum Noise Characterisation and Mitigation via Qiskit Simulation

**Final Year Individual Project — University of Manchester**  
Department of Electrical and Electronic Engineering  
Academic Year 2026–27

---

## Project overview

This project investigates how noise affects quantum systems and how it can be mitigated through quantum error correction (QEC). Using IBM's Qiskit framework, five QEC codes are implemented, simulated, and validated on real IBM quantum hardware — allowing a direct comparison between ideal simulation and real-world quantum noise.

The project is motivated by the fundamental challenge in quantum computing: qubits are extremely fragile and susceptible to environmental noise, making error correction one of the most critical problems in the field.

Prior to the project start, a structured pre-study period will cover Python, quantum mechanics fundamentals, and Qiskit — ensuring the full 9-month project period is dedicated to implementation, analysis, and write-up. All code, results, and documentation will be version-controlled and backed up via GitHub throughout the project.

---

## Objectives

- Understand and characterise key quantum noise models (bit-flip, phase-flip, depolarising)
- Implement five quantum error correcting codes of increasing complexity
- Simulate and compare the effectiveness of each code under different noise conditions
- Validate results on real IBM quantum hardware via IBM Quantum (free tier)
- Compare simulation results against real hardware results and analyse discrepancies
- Analyse performance trade-offs (qubit overhead vs error suppression)

---

## Pre-study (before project start — summer/holiday period)

| Topic | Description |
|-------|-------------|
| Python | Core Python programming fundamentals |
| Quantum mechanics | Qubits, superposition, entanglement, measurement |
| Qiskit | Quantum circuit basics, Qiskit Aer simulator |
| QEC concepts | Key papers and introductory reading on error correction |

---

## Timeline

| Month | Phase | Description |
|-------|-------|-------------|
| 1 | Repetition & 3-qubit code | Implement, simulate, and validate on real hardware |
| 2–3 | Steane code (7-qubit) | Implement, simulate, and validate on real hardware |
| 3–4 | Shor code (9-qubit) | Implement, simulate, and validate on real hardware |
| 5–6 | Surface code (17-qubit) | Implement via simulation only |
| 7–8 | Analysis & hardware validation | Compare all codes, visualise results, run hardware jobs |
| 8–9 | Report & presentation | Final write-up and project submission |

---

## Tools and technologies

- **Python** — primary language (fundamentals to be completed before project start)
- **Qiskit** — quantum circuit design and simulation
- **Qiskit Aer** — noise model simulation
- **IBM Quantum** — real quantum hardware validation (free tier)
- **Matplotlib / NumPy** — data analysis and visualisation
- **GitHub** — version control and full project backup throughout

---

## Scope

### Phase 1 — Repetition code
The most basic QEC concept. Encodes information redundantly across multiple qubits to detect and correct single errors. Starting point for understanding the QEC workflow in Qiskit.
**Hardware validation: yes**

### Phase 2 — 3-qubit bit-flip code
Encodes 1 logical qubit into 3 physical qubits and corrects single bit-flip errors using majority voting.
**Hardware validation: yes**

### Phase 3 — Steane code (7-qubit)
First code to use the stabiliser formalism. Corrects any single-qubit error using 7 physical qubits.
**Hardware validation: yes**

### Phase 4 — Shor code (9-qubit)
Corrects both bit-flip and phase-flip errors simultaneously. First complete QEC code.
**Hardware validation: yes**

### Phase 5 — Surface code (17-qubit)
The most practical QEC code used by Google and IBM in real quantum hardware. Simulated at 17-qubit scale using Qiskit Aer only due to hardware complexity.
**Hardware validation: simulation only**

### Phase 6 — Comparative analysis
All five codes compared across varying noise levels. Metrics include logical error rate, qubit overhead, and circuit depth. Simulation vs real hardware results analysed and discussed.

Throughout all phases, relevant literature and research papers will be reviewed on an ongoing basis to address knowledge gaps as they arise and ensure implementations remain grounded in current research.

---

## Expected outcomes

- Working Qiskit implementations of five QEC codes
- Benchmarking data across noise models and code types
- Simulation vs real hardware comparison and analysis
- Clear visualisation of error suppression effectiveness
- Final project report and presentation

---

*This document is a proposal for a bespoke final year individual project for supervisor approval.*
