# Hybrid Quantum Circuit Simulator

A Python-based quantum computing simulator built from scratch using NumPy. This project models qubit state vectors, applies fundamental quantum gates (Pauli-X, Hadamard, CNOT) via matrix multiplication, and tracks performance KPIs like execution time and memory footprint. 

This simulator was developed for the Phoenix Association IT Team Induction (2026-27).

## Features
*   **State Representation:** Qubits modeled as 2D and 4D complex column vectors.
*   **Gate Execution:** Custom implementations of X, H, and CNOT gates using tensor products and dot products.
*   **Circuit Workflow:** Generates the Bell State, demonstrating quantum entanglement and 50/50 probability distributions.
*   **KPI Tracking:** Measures execution time, state vector scaling, and memory usage.

## Setup Instructions
1. Ensure you have Python 3.x installed on your system.
2. Clone this repository to your local machine.
3. Install the required dependency (NumPy) using pip:
   `pip install numpy`

## How to Run
Navigate to the project directory in your terminal and execute the main Python script:
`python simulator.py`

The console will output the initial state, the gate transformations, the final measured probabilities for the Bell State, and the tracked KPIs.
