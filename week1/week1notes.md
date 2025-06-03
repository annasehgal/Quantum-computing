# Intro to qubits, complex numbers, Block Sphere
#
# What is Quantum Computing?
* Quantum computing uses the principles of quantum physics to perform calculations, offering potential for solving problems that are intractable for classical computers. It leverages concepts like superposition and entanglement to process information in a way that classical computers cannot, potentially leading to faster or more efficient solutions. 

### End of Moore's Law:     
 The "end of Moore's Law," which states that the number of transistors on a microchip doubles roughly every two years, doesn't necessarily mean the end of progress in computing. While miniaturization of transistors is approaching physical limits, quantum computing represents a potential paradigm shift. Quantum computing offers a new way to perform calculations, using quantum bits (qubits) instead of classical bits, potentially leading to faster and more efficient solutions for certain types of problems.

## Week 1: Introduction, complex numbers, qubits, and Bloch Sphere representation
## 1. Bloch Sphere

![Bloch Sphere](https://upload.wikimedia.org/wikipedia/commons/e/e9/Sphere_bloch.jpg)

**Definition**:  
The **Bloch Sphere** is a geometrical representation of the pure state space of a qubit, the fundamental unit of quantum information. It is used to visualize the state of a qubit as a point on or inside a sphere.

**Purpose**:  
Helps in visualizing **superposition** and the effects of **quantum gates** on qubits.

**Key Concept**:  
Every point on the surface of the sphere represents a possible pure qubit state.

---

## 2. Qubit (Quantum Bit)

![Quantum State Visualization](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*w9516UckuSEBQdiUOoiHbQ.png)

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

## 7. Skepticism About Quantum Computing
- Noise and decoherence grow exponentially with qubit count, threatening scalability.
- Google's 2019 Quantum Supremacy experiment validates quantum advantage.
- Error correction and noise mitigation remain critical research areas.

## 8. Quantum Decoherence and Operational Challenges
- Decoherence disrupts quantum information, requiring extreme cooling (~0 K).
- Quantum chips are sensitive and error-prone.
- Sustained quantum coherence is a major engineering challenge.

## 9. Quantum Computing Architectures
- Various qubit implementations: superconducting circuits, trapped ions, neutral atoms, cat qubits.
- Hybrid quantum-classical computing frameworks like IBM Qiskit enable development.
- Quantum outputs are probabilistic, requiring statistical validation.

## 10. Quantum Mechanics Key Concepts
- Particles exist as wavefunctions representing probabilities.
- Measurement collapses these wavefunctions to definite states.

## 11. Bits vs Qubits
- Bits = 0 or 1.
- Qubits = superpositions α|0⟩ + β|1⟩ with complex amplitudes.

## 12. Superposition
- Qubits represent multiple states simultaneously.
- Measurement probabilistically collapses superpositions.

## 13. Entanglement
- Qubits share correlated states affecting each other instantaneously.
- Essential for quantum communication and algorithms.

## 14. Interference
- Quantum states interfere constructively or destructively.
- Algorithms exploit this to amplify correct results.

## 15. Quantum Computing Workflow
1. Initialize qubits to superposition.
2. Apply phase shifts and gates.
3. Use interference to enhance solution probabilities.
4. Measure qubits to obtain results.
5. Repeat for statistical confidence.

## 16. Wave-Particle Duality and Slit Experiments

### Types of Slits:
1. **Single Slit:** Diffraction pattern from one narrow slit showing wave spreading.
2. **Double Slit:** Interference pattern from two slits, illustrating wave-particle duality.
3. **Multiple Slits:** Complex interference patterns from many slits (diffraction grating).
4. **Variable Slit Width:** Changing slit width affects diffraction pattern size and intensity.

### Double-Slit Experiment
- Particles behave as waves when unmeasured, creating interference.
- Measurement collapses wavefunction, destroying interference pattern.
- Demonstrates fundamental quantum measurement impact.

---

# Chapter 1: Complex Numbers
