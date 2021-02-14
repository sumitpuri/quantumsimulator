# Quantum Simulator

This [jupyter notebook](QuantumSimulator.ipynb) implements the Quantum Simulator for below Quantum Gates.

Operator | Gate 
---|---
Pauli-X | X
Hadamard | H
Controlled Not | CNOT, CX

Known limitation:
  - CNOT Gate can be applied only on consecutive qubits where target qubit is greater than the control qubit. 
  - The simulator is not programmed to check the scenario if the qubit on which the Quantum Gate needs to be applied is defined within the total number of qubits. <br>
    In other words, the user needs to be cautious that if total number of qubits defined are 3, the Quantum Gate can be applied to only [0], [1], or [2] target qubits.
