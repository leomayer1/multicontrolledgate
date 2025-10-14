# multicontrolledgate

Implementations in qiskit of controlled quantum gates from scratch. Includes the following functions:

### ZYDecomposition(U)

**Inputs:**
  - $U$ - a 2x2 unitary matrix.

**Returns:** A tuple of real numbers $(\alpha,\beta,\gamma,\delta)$ such that $U = e^{i\alpha}R_z(\beta)R_y(\gamma)R_z(\delta)$.

### SingleControlledGate(U)

**Inputs**
  - $U$ - a 2x2 unitary matrix.

**Returns:** A QuantumCircuit on two qubits realizing the controlled $U$ operation.

### MultiControlledGate(n, U)

**Inputs**
  - n - a positive integer.
  - $U$ - a 2x2 unitary matrix.

**Returns:** A QuantumCircuit on $n+1$ qubits realizing the multicontrolled $U$ operation.


### MultiControlledGate2(n, U)

**Inputs**
  - n - a positive integer.
  - $U$ - a 2x2 unitary matrix.

**Returns:** A QuantumCircuit on $n+1$ qubits realizing the multicontrolled $U$ operation, but in a more space efficient manner.

