# Day 21 Concepts — Variational Quantum Eigensolver (VQE)

## Why this day matters

Learn the hybrid variational pattern used heavily in near-term quantum research.

## 1. Variational principle

For a Hamiltonian, the expected energy of a trial state is an upper bound on the ground-state energy under standard assumptions.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 2. Ansatz

A parameterized circuit prepares candidate states.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 3. Expectation values

The Hamiltonian is decomposed into measurable terms whose expectation values are estimated from circuit samples.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 4. Classical optimizer

A classical routine updates circuit parameters to reduce estimated energy.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 5. Trade-offs

Ansatz expressibility, trainability, shot cost, noise, optimizer behavior, and measurement grouping all affect performance.

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
