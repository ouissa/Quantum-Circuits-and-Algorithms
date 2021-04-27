# Quantum Circuits and Algorithms

## About the Project

This project is an introduction to quantum circuits and algorithms based on the Qiskit textbook and linear algebra rules.

## Description: how does it relate to linear algebra?

Currently, this project has 4 files each about a quantum circuit that demonstrates some of the basics. More advanced circuits will be introduced later. I attached links to Google Colab for each file so that you can play with the values and see how it is affected by the circuit.

### 1. Single Quantum Computing Circuit

This file is the first code I have written in this repository, it created a simple quantum circuit with 8 qubits, and 8 bits to store the measured value in the qubits.

Try it [here](https://drive.google.com/file/d/1rtqDB0WWY7b9ADPQB_p35we6rNQ5-S9e/view?usp=sharing).

### 2. Quantum Half Adder

This second code tries to implement a quantum half adder. This was the opportunity to introduce some quantum gates like X-gate and the Toffoli-gate.

Try it [here](https://drive.google.com/file/d/1yfzlspEWmmp4bZW1BgwDE_Vh5msMynja/view?usp=sharing).

### 3. Exploring Qubits

This code introduces qubits, and how they are represented. It shows how a qubit is represented as a state vector, and how they are represented visually on the block sphere. This part also shows how 0 and 1 are represented by the 2 basis vectors \1> and |1> that are orthogonal, and how any other qubit can be written as a linear combination of these two (complex coefficients).

Try it [here](https://drive.google.com/file/d/1zgsrMufD_MZYhnoFZSM4Wb96IBUqiMgZ/view?usp=sharing).

### 4. Single Quantum Gates

This code introduces single quantum gates and how they are represented mathematically. It shows how quantum gates are just linear transformations that are applied on state vectors of the qubit. The code shows how each gate transforms a qubit visually on the Bloch sphere (rotation on the z-axis, on the vector [1, 0, 1]...).

## Future Work

- Adding multiple quantum gates.
- Quantum Algorithms

## Resources

- [Qiskit Textbook](https://qiskit.org/textbook)