# 3rd-Year-Project-QEC-Proposal
UoM Soochan Kim's Final Year Project Proposal

Department of Electrical and Electronic Engineering  
Academic Year 2026–27

---

## Project overview

This project investigates how noise affects quantum systems and how it can be mitigated through quantum error correction (QEC). Using IBM's Qiskit framework, various noise models and error correcting codes are implemented and analysed through simulation — with no physical quantum hardware required.

The project is motivated by the fundamental challenge in quantum computing: qubits are extremely fragile and susceptible to environmental noise, making error correction one of the most critical problems in the field.

---

## Objectives

- Understand and characterise key quantum noise models (bit-flip, phase-flip, depolarising)
- Implement quantum error correcting codes of increasing complexity
- Simulate and compare the effectiveness of each code under different noise conditions
- Analyse performance trade-offs (qubit overhead vs error suppression)

---

## Timeline

| Month | Phase | Description |
|-------|-------|-------------|
| 1–2 | Background study | Quantum mechanics fundamentals, Qiskit, noise models |
| 3–4 | 3-qubit code | Implement bit-flip and phase-flip codes |
| 4–5 | Shor code | Implement 9-qubit Shor code, handle both error types |
| 5–6 | Surface code | Implement 17-qubit surface code simulation |
| 7–8 | Analysis | Compare all codes, visualise results |
| 8–9 | Report & presentation | Final write-up and project submission |

---

## Tools and technologies

- **Python** — primary language
- **Qiskit** — quantum circuit design and simulation
- **Qiskit Aer** — noise model simulation
- **Matplotlib / NumPy** — data analysis and visualisation

---

## Scope

### Phase 1 — 3-qubit bit-flip code
The simplest QEC code. Encodes 1 logical qubit into 3 physical qubits and corrects single bit-flip errors using majority voting.

### Phase 2 — Shor code (9-qubit)
Extends the 3-qubit approach to correct both bit-flip and phase-flip errors simultaneously. First complete QEC code.

### Phase 3 — Surface code (17-qubit)
The most practical QEC code used by Google and IBM in real quantum hardware. Simulated at 17-qubit scale using Qiskit Aer.

### Phase 4 — Comparative analysis
Performance of all three codes compared across varying noise levels. Metrics include logical error rate, qubit overhead, and circuit depth.

---

## Expected outcomes

- Working Qiskit implementations of three QEC codes
- Benchmarking data across noise models and code types
- Clear visualisation of error suppression effectiveness
- Final project report and presentation

---

## References

- Nielsen & Chuang, *Quantum Computation and Quantum Information* (2000)
- Qiskit documentation — https://docs.quantum.ibm.com
- Vijayan et al., quantum noise and mitigation research, University of Manchester

---

*This project is proposed as a bespoke final year project under the supervision of Dr Jayadev Vijayan, Quantum Engineering Lab, University of Manchester.*
