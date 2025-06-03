# Intro to qubits, complex numbers, Block Sphere

# What is Quantum Computing?
* Quantum computing uses the principles of quantum physics to perform calculations, offering potential for solving problems that are intractable for classical computers. It leverages concepts like superposition and entanglement to process information in a way that classical computers cannot, potentially leading to faster or more efficient solutions. 

### End of Moore's Law:     
 The "end of Moore's Law," which states that the number of transistors on a microchip doubles roughly every two years, doesn't necessarily mean the end of progress in computing. While miniaturization of transistors is approaching physical limits, quantum computing represents a potential paradigm shift. Quantum computing offers a new way to perform calculations, using quantum bits (qubits) instead of classical bits, potentially leading to faster and more efficient solutions for certain types of problems.

## Week 1: Introduction, complex numbers, qubits, and Bloch Sphere representation
## 1. Bloch Sphere

**Definition**:  
The **Bloch Sphere** is a geometrical representation of the pure state space of a qubit, the fundamental unit of quantum information. It is used to visualize the state of a qubit as a point on or inside a sphere.

**Purpose**:  
Helps in visualizing **superposition** and the effects of **quantum gates** on qubits.

**Key Concept**:  
Every point on the surface of the sphere represents a possible pure qubit state.

---

## 2. Qubit (Quantum Bit)

**Definition**:  
A **qubit** is the basic unit of information in a quantum computer. Unlike a classical bit (which is either 0 or 1), a qubit can exist in a **superposition** of both 0 and 1 simultaneously.

**Key Properties**:
- **Superposition**: Qubits can hold multiple states at once.
- **Entanglement**: Qubits can be linked so that the state of one affects the state of another.
- **Measurement**: Measuring a qubit collapses its state to either 0 or 1.

---

## 3. Classical vs Quantum Computing

| Feature          | Classical Computing             | Quantum Computing                           |
|------------------|----------------------------------|----------------------------------------------|
| Basic Unit       | Bit (0 or 1)                     | Qubit (0, 1, or both in superposition)       |
| Processing       | Logic gates on bits              | Quantum gates on qubits                      |
| Components       | Transistors                      | Photons, ions, superconducting circuits      |
| Parallelism      | Limited                          | Massive via superposition and entanglement   |
| Advantages       | Reliable, well-understood        | Potential exponential speedup for some tasks |

---

## 4. How Quantum Computers Work

- **Input**: Quantum data (qubit states)
- **Operations**: Quantum gates (e.g., Hadamard, Pauli-X, CNOT)
- **Output**: Qubit states, which are measured to obtain classical bits

**Technologies Used**:
- **Photons**: Act like transistors in optical quantum computers.
- **Lasers**: Used to manipulate photon or ion states.
- **Quantum Gates**: Perform operations analogous to logic gates.

---

## 5. Moore’s Law & Quantum Limits

**Moore’s Law**:  
The number of transistors on a chip doubles approximately every two years, historically driving exponential growth in classical computing power.

**Quantum Limitation**:
- Around **5nm**, quantum tunneling becomes a serious issue.
- Electrons may unpredictably tunnel through barriers, leading to potential transistor failure.
- **Cost Concern**: Manufacturing at 5nm scale is projected to cost ~$20 billion for the required equipment.

---

## 6. Why Quantum Computing Matters

- **Speed**: Can solve specific problems (like factoring) exponentially faster than classical algorithms.
- **Complexity**: Handles problems with vast numbers of variables (e.g., optimization, cryptography, simulation).
- **Use Cases**:
  - Cryptography (Shor’s algorithm)
  - Drug discovery and molecular modeling
  - Optimization problems (logistics, finance)

> **Note**: Quantum computing is not a replacement for classical computing, but a powerful complement for certain tasks.

