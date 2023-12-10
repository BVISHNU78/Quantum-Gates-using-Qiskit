# Quantum-Gates-using-Qiskit
The fundamental element of quantum computing is the quantum circuit. A quantum circuit is a computational routine consisting of coherent quantum operations on quantum data, such as qubits. It is an ordered sequence of quantum gates, measurements and resets, which may be conditioned on real-time classical computation. A set of quantum gates is said to be universal if any unitary transformation of the quantum data can be efficiently approximated arbitrarily well as a sequence of gates in the set. Any quantum program can be represented by a sequence of quantum circuits and classical near-time computation.

In Qiskit, this core element is represented by the QuantumCircuit class. Below is an example of a quantum circuit that makes a three-qubit GHZ state defined as:
∣ψ⟩=(∣000⟩+∣111⟩)/2
∣ψ⟩=(∣000⟩+∣111⟩)/2
Quantum Circuit with conditionals

When building a quantum circuit, there can be interest in applying a certain gate only if a classical register has a specific value. This can be done with the InstructionSet.c_if() method.

In the following example, we start with a single-qubit circuit formed by only a Hadamard gate (HGate), in which we expect to get ∣0⟩∣0⟩ and ∣1⟩∣1⟩ with equal probability.
