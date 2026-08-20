# Day 07 Concepts — Multi-Qubit States and Tensor Products

## Why this day matters

Scale your mental model from one qubit to registers of qubits.

## 1. Tensor product

The joint state space of multiple qubits is formed with the tensor product.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 2. Basis growth

n qubits have 2^n computational-basis states, which is why state-vector simulation becomes expensive as n increases.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 3. Separable states

A multi-qubit state is separable if it can be written as a tensor product of individual subsystem states.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 4. Correlations

Joint distributions can contain classical or quantum correlations. Entanglement is specifically non-separable quantum correlation.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 5. Indexing conventions

Frameworks may display bitstrings in conventions that can appear reversed relative to qubit labels, so always verify ordering.

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
