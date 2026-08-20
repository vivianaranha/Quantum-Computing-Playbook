# Day 19 Concepts — Quantum Phase Estimation

## Why this day matters

Understand how eigenphases can be extracted through controlled powers and inverse QFT.

## 1. Eigenvalue problem

If U|ψ⟩ = e^{2πiθ}|ψ⟩, phase estimation aims to estimate θ.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 2. Counting register

Ancilla qubits hold a phase-encoded binary approximation.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 3. Controlled powers

Controlled-U^(2^k) operations accumulate phase with increasing significance.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 4. Inverse QFT

The inverse QFT converts the encoded relative phases into a measurable binary estimate.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 5. Algorithmic importance

Phase estimation supports more advanced algorithms in chemistry, linear algebra, and factoring, though resource requirements can be substantial.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## Connect the ideas

Do not treat these concepts as isolated vocabulary. Ask how they change the way you predict a circuit's output, evaluate a hardware result, or judge an application claim.

## What to be able to say out loud

Explain today's topic in three levels:

1. **30 seconds:** one-sentence definition and why it matters.
2. **2 minutes:** include one mathematical or circuit-level example.
3. **5 minutes:** include assumptions, limitations, and one connection to another quantum concept.

## Common learning trap

The most common mistake is memorizing definitions without predicting behavior. Whenever possible, write down what you expect to happen **before** calculating, simulating, or measuring.
