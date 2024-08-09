# Quantum_Algo_Project
The project focuses on the implementation of quantum cryptographic quantum protocol alogoritm. This quantum project utilizes trapdoor claw-free functions based on Rabin's function and the Diffie_Hellman problem. The implementation consists of three rounds of interaction between a quantum prover and a classical verifier. 
### The first round 
A multi-qubit superposition is generated over two bitstrings, which are cryptographically challenging to compute classically. 
### The second round maps to this superposition onto state of one ancilla qubit, retainting enough information to ensure that resulting single qubit is also hard to compute classically. The final round performs CHSH-type Bell's inequality measurement, the result oof which is cryptographically protected. 
# OPTIMIZATION AND RESULTS 
## Quantum Circuit Simulation
The quantum circuits were simulated using the Classiq Python SDK, which enabled a comparison of circuit depth and width across several hardware simulators.

## Optimization and Hardware Simulation
The circuits were optimized for depth, with a constraint of using more than 50 qubits for simulation on the Azure Quantum simulator. The synthesized circuit requires a depth of 255 levels on the Azure Quantum IonQ hardware simulator.
