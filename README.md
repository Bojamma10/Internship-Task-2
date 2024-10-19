# Internship-Task-2

Project Description
Overview
The Quantum Fourier Transform (QFT) is the quantum analogue of the discrete Fourier transform (DFT) and plays a crucial role in various quantum algorithms. This project implements a 5-qubit QFT on a quantum circuit using the Qiskit library. The quantum circuit consists of the following:

A Hadamard gate applied to each qubit.
Controlled phase gates between qubits to introduce the appropriate phase shifts.
Finally, measurement operations to read out the qubit states.
QFT Circuit Implementation
The circuit uses the following steps:

Quantum and Classical Registers:

A 5-qubit quantum register q.
A 5-bit classical register c.
Hadamard Gates:

A Hadamard gate is applied to each qubit to create a superposition state.
Controlled Phase Gates:

Phase shift gates (cp) are applied to pairs of qubits to encode phase relationships between the qubits.
Measurement:

Each qubit is measured and stored in the corresponding classical bit.
