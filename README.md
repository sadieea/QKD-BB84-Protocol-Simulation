# QKD-BB84-Protocol-Simulation

This repository contains a simulation of the BB84 Quantum Key Distribution (QKD) protocol, one of the first and most well-known quantum cryptography protocols. BB84 leverages quantum mechanics principles to enable two parties to securely exchange cryptographic keys over potentially insecure channels, ensuring data privacy against eavesdroppers.

Project Overview
The BB84 protocol uses qubits in various quantum states to encode bits, allowing for secure key exchange by detecting any interception attempts by a third party. In this simulation, we model the steps of BB84 using Qiskit to illustrate key concepts in quantum cryptography, such as superposition, measurement, and basis selection.

Features
Encoding & Transmission: Simulates qubit preparation in chosen bases (rectilinear and diagonal).
Measurement: Models measurement process by the receiver in randomly chosen bases.
Error Detection: Detects eavesdropping by analyzing basis mismatches and error rates.
Key Agreement: Demonstrates the secure key agreement process between sender and receiver.

Getting Started
Install dependencies:
pip install qiskit

Run the simulation: Use the provided Jupyter notebook to run the protocol steps and visualize results.

License
This project is licensed under the MIT License.
