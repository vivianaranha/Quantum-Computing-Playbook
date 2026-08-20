# 30-Day Quantum Computing Playbook

A day-by-day, GitHub-ready learning repository for building a practical foundation in quantum computing.

This playbook is designed to move from **core concepts → math → gates → circuits → noise → algorithms → hardware → applications → capstone** in 30 focused days.

## Who this is for

- Software engineers moving into quantum computing
- AI / ML engineers exploring quantum
- Students building a structured self-study path
- Technical leaders who want enough depth to evaluate quantum claims
- Developers preparing for quantum-computing interviews or projects

## Suggested daily rhythm

| Block | Time | Goal |
|---|---:|---|
| Learn | 30–45 min | Read the concept notes |
| Work | 30–45 min | Complete the hands-on lab |
| Practice | 20–30 min | Do the exercises without notes |
| Check | 10–15 min | Take the self-check quiz |
| Build | 15–30 min | Add the day's artifact to your portfolio |

A typical day is **1.5–2.5 hours**. If you have less time, complete the concept notes, one exercise, and the build artifact.

## Repository structure

Each day contains:

- `README.md` — goals, daily plan, and completion checklist
- `01-concepts.md` — core theory
- `02-hands-on-lab.md` — practical activity
- `03-exercises.md` — practice prompts
- `04-quiz.md` — self-check with answers
- `05-build-artifact.md` — a small portfolio output
- `06-review-notes.md` — reflection and spaced-repetition prompts

Additional root-level resources include a roadmap, glossary, formula sheet, hardware comparison guide, and project rubric.

## Principles

1. **Understand before memorizing.**
2. **Predict before running a circuit.**
3. **Always compare against a classical baseline.**
4. **Treat noise and hardware constraints as part of the problem.**
5. **Do not confuse a toy demonstration with quantum advantage.**
6. **Use simulators to learn; use hardware to understand reality.**
7. **Write down what you learned every day.**

## 30-day roadmap

- **Day 01: Quantum Computing Foundations** — Build a mental model of what quantum computing is, what it is not, and where it can matter.
- **Day 02: Bits vs Qubits** — Understand how classical bits and qubits represent information differently.
- **Day 03: Essential Math: Complex Numbers, Vectors, and Dirac Notation** — Learn only the linear algebra needed to read and reason about quantum circuits.
- **Day 04: Measurement, Probability, and Amplitudes** — Connect quantum states to the classical data obtained from measurements.
- **Day 05: Single-Qubit Gates** — Develop intuition for the most common one-qubit operations.
- **Day 06: Rotation Gates and Phase** — Move beyond fixed gates and learn parameterized quantum operations.
- **Day 07: Multi-Qubit States and Tensor Products** — Scale your mental model from one qubit to registers of qubits.
- **Day 08: Entanglement and Bell States** — Understand entanglement operationally through the simplest two-qubit examples.
- **Day 09: Quantum Circuits and Workflow** — Learn the standard prepare → transform → measure → analyze workflow.
- **Day 10: Interference and Phase Engineering** — Understand the mechanism behind many quantum algorithmic speedups.
- **Day 11: Quantum Tools, SDKs, and Simulators** — Understand the software ecosystem and choose tools by purpose rather than brand.
- **Day 12: Noise, Decoherence, and NISQ Systems** — Learn why real quantum hardware behaves differently from ideal circuits.
- **Day 13: Error Mitigation vs Quantum Error Correction** — Separate near-term mitigation techniques from fault-tolerant error correction.
- **Day 14: Quantum Hardware Modalities** — Compare how different physical platforms implement qubits and gates.
- **Day 15: First Quantum Algorithm: Deutsch-Jozsa** — Use a simple oracle problem to see interference-driven algorithm design.
- **Day 16: Bernstein-Vazirani and Oracle Thinking** — Learn how hidden structure can be extracted through phase and interference.
- **Day 17: Grover's Search and Amplitude Amplification** — Understand quadratic speedup for unstructured search in the query model.
- **Day 18: Quantum Fourier Transform** — Learn the phase-to-frequency transform behind several important algorithms.
- **Day 19: Quantum Phase Estimation** — Understand how eigenphases can be extracted through controlled powers and inverse QFT.
- **Day 20: Shor's Algorithm and Factoring** — Connect period finding, QFT, and public-key cryptography.
- **Day 21: Variational Quantum Eigensolver (VQE)** — Learn the hybrid variational pattern used heavily in near-term quantum research.
- **Day 22: Quantum Approximate Optimization Algorithm (QAOA)** — Explore variational optimization with alternating problem and mixer operators.
- **Day 23: Quantum Machine Learning** — Evaluate QML ideas without confusing novelty with advantage.
- **Day 24: Quantum Optimization Applications** — Translate business optimization problems into quantum-compatible mathematical forms.
- **Day 25: Quantum Chemistry and Materials** — Understand why simulation of quantum systems is a natural quantum-computing target.
- **Day 26: Quantum Teleportation, Communication, and Security** — Use teleportation to connect entanglement, measurement, classical communication, and state transfer.
- **Day 27: Hybrid Quantum-Classical Workflows** — Design realistic architectures where quantum systems are accelerators, not standalone applications.
- **Day 28: Benchmarking, Complexity, and Resource Estimation** — Learn how to evaluate quantum claims with technical discipline.
- **Day 29: Capstone: Build a Quantum Computing Mini-Project** — Apply the full workflow to a small, defensible project.
- **Day 30: Review, Interview Readiness, and the Next 90 Days** — Consolidate the 30-day foundation into a durable learning path.

## Recommended tooling

You can complete the conceptual material without any cloud account. For circuit labs, choose one SDK and stay with it long enough to build fluency.

Common choices include:

- **Qiskit** — broad circuit-model ecosystem and IBM Quantum integration
- **Cirq** — circuit-oriented framework associated with Google Quantum AI
- **PennyLane** — strong fit for hybrid and differentiable quantum workflows
- **Vendor SDKs** — useful when targeting a specific hardware provider

For this playbook, SDK-specific code is intentionally optional. The goal is to learn the ideas well enough that switching frameworks later is manageable.

## Completion standard

You have completed the playbook when you can:

- Explain a qubit mathematically and intuitively
- Reason about amplitudes, phase, and measurement
- Build and debug simple circuits
- Create and explain Bell states
- Distinguish ideal simulation from noisy execution
- Explain error mitigation vs quantum error correction
- Compare major hardware modalities
- Explain Grover, QFT, QPE, Shor, VQE, and QAOA at a high level
- Evaluate a quantum use case against classical baselines
- Complete and communicate a small capstone project


## Related Courses

[100 Days of Quantum Computing Coding](https://www.udemy.com/course/100-days-of-quantum-computing-coding/?referralCode=F821A93716FB2BA1DE3D)

[Quantum Physics to Quantum Computing Masterclass](https://www.udemy.com/course/quantum-physics-to-quantum-computing-masterclass/?referralCode=1077C792870CE0E724B0)

[Quantum Computing for Decision Makers: Executive Essentials](https://www.udemy.com/course/quantum-computing-for-decision-makers-executive-essentials/?referralCode=852EE6ACEA1F8EF5EF4B)

[Quantum Kitchen: Cooking Up Concepts in Quantum Computing](https://www.udemy.com/course/quantum-computing-kitchen/?referralCode=C49FA8E5CFFC0747E60C)

[AI & Quantum Computing Mastery: From Zero to Expert Bootcamp](https://www.udemy.com/course/ai-quantum-computing-mastery-from-zero-to-expert-bootcamp/?referralCode=1BB57002E444B06E4E39)
