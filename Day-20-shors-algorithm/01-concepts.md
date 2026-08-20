# Day 20 Concepts — Shor's Algorithm and Factoring

## Why this day matters

Connect period finding, QFT, and public-key cryptography.

## 1. Factoring problem

Shor's algorithm factors integers in polynomial time on an ideal fault-tolerant quantum computer using a quantum period-finding subroutine.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 2. Classical wrapper

Several steps, including random selection, gcd checks, and factor extraction, are classical.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 3. Quantum core

The quantum part estimates periodic structure related to modular exponentiation.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 4. Cryptographic impact

Large-scale fault-tolerant quantum computing would threaten widely deployed public-key systems based on factoring or discrete logarithms, motivating post-quantum cryptography migration.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 5. Resource reality

Cryptographically relevant factoring requires fault-tolerant logical qubits and very large physical-resource budgets under realistic assumptions.

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
