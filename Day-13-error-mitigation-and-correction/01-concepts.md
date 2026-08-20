# Day 13 Concepts — Error Mitigation vs Quantum Error Correction

## Why this day matters

Separate near-term mitigation techniques from fault-tolerant error correction.

## 1. Error mitigation

Mitigation estimates or reduces the effect of noise without encoding a durable logical qubit that can be corrected repeatedly.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 2. Quantum error correction

QEC encodes logical information redundantly across physical qubits so selected errors can be detected and corrected without directly measuring the logical state.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 3. Syndrome

Ancilla-assisted syndrome measurements reveal information about errors while preserving encoded logical information.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 4. Threshold idea

Fault-tolerant architectures require physical error rates low enough that adding error-correction structure improves logical reliability.

**Think about it:** What assumption does this idea rely on, and how would you recognize it in a circuit or system?

## 5. Overhead

Useful fault-tolerant computation may require many physical qubits, operations, and classical control resources per logical qubit.

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
