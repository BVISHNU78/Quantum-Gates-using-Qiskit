# Quantum-Gates-using-Qiskit
The fundamental element of quantum computing is the quantum circuit. A quantum circuit is a computational routine consisting of coherent quantum operations on quantum data, such as qubits. It is an ordered sequence of quantum gates, measurements and resets, which may be conditioned on real-time classical computation. A set of quantum gates is said to be universal if any unitary transformation of the quantum data can be efficiently approximated arbitrarily well as a sequence of gates in the set. Any quantum program can be represented by a sequence of quantum circuits and classical near-time computation.

In Qiskit, this core element is represented by the QuantumCircuit class. Below is an example of a quantum circuit that makes a three-qubit GHZ state defined as:
∣ψ⟩=(∣000⟩+∣111⟩)/2
∣ψ⟩=(∣000⟩+∣111⟩)/2
Quantum Circuit with conditionals

When building a quantum circuit, there can be interest in applying a certain gate only if a classical register has a specific value. This can be done with the InstructionSet.c_if() method.

In the following example, we start with a single-qubit circuit formed by only a Hadamard gate (HGate), in which we expect to get ∣0⟩∣0⟩ and ∣1⟩∣1⟩ with equal probability.

![download](https://github.com/user-attachments/assets/ccb621c8-0f89-439d-90b3-b35cbafe43d0)
# Quantum Gates using Qiskit

An educational project demonstrating the implementation and simulation of fundamental quantum gates using IBM's Qiskit framework.

## 🚀 Project Overview

This repository showcases the creation and simulation of basic quantum gates such as Hadamard, Pauli-X, Pauli-Y, Pauli-Z, CNOT, and others using Qiskit. It serves as a learning resource for beginners exploring quantum computing and quantum circuits.

## Features

- Implementation of standard quantum gates (Hadamard, Pauli-X/Y/Z, CNOT, Toffoli, etc.)  
- Quantum circuit construction and visualization  
- Simulation of gate operations using Qiskit Aer backend  
- Measurement and result analysis  
- Step-by-step explanations of each gate's function and effect on qubits  

## Tech Stack

- Python 3.x  
- Qiskit (IBM Quantum SDK)  
- Jupyter Notebook / Python scripts for code demonstrations  

## Installation

1. Clone the repository:

```bash
git clone https://github.com/BVISHNU78/Quantum-Gates-using-Qiskit.git
cd Quantum-Gates-using-Qiskit
