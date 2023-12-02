# Bernstein-Vazirani Circuit
### Creating an illustration of the circuit of the Bernstein-Vazirani algorithm using python and libraries such as qiskit and matplotlib.

⚙️ For context : The Bernstein-Vazirani algorithm is used to determine a hidden binary string by querying an oracle. This algorithm showcases quantum parallelism advantages over classical algorithms, especially for this specific problem.

💡 : In this code, I created two functions, one for the oracle of the Bernstein-Vazirani algorithm and the another for the circuit. 

The first function has the number of qubits and the secret number ( the hidden binary string ) as its entries and it returns the oracle in the form of a quantum gate.

The second function has the gate ( oracle ) as its entry and it returns the whole Bernstein-Vazirani quantum circuit.

In this project, I used both matplotlib and qiskit_visualization to visualize the circuit. I also used qiskit to use and manipulate the quantum circuits, gates, qubits and bits.
