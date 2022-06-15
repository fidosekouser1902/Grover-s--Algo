# Grover-s--Algo

## Solving Boolean Satisfiability Problem using Grover’s Algorithm
### Motivation
   Grover’s algorithm, also known as the quantum search algorithm, is a quantum algorithm designed by Los Grover in 1996 to search for an element in an unsorted array quadratically faster than the classical linear search for large datasets. In this project we will solve a particular boolean satisfiability problem using Grover's algorithm.

Boolean variables can take the values 'true' or 'false'. Given the constraints on the boolean variables, we can form a boolean output function, and if for some assigned values of the variables the function turns out to be true, then we say that the function is satisfiable. By solving a Boolean SAT problem, we want to determine all the input combinations into a boolean function such that the output is true. Since we will be searching through the combinations, this can be solved using Grover's algorithm.

## Problem Statement
  Frank wants to throw a dinner party to celebrate Alice and Bob’s engagement. He is also considering inviting their mutual friends Charles, Dave and Eve. However, he is aware that Charles will come to the party only if Dave comes without Eve. Frank wants to know what possible combinations of invitations he can write for his friends Alice, Bob, Charles, Dave and Eve.

Help Frank calculate all the possible combinations using Grover’s algorithm.

## Roadmap
- Learning about qubits, quantum gates and quantum circuits.
- Getting acquainted with the Grover’s algorithm and programming in Qiskit or a similar framework.
- Creating an oracle that satisfies the given conditions using diagonal operators.
- Using a state-vector simulator to calculate the amplitudes of the states prior to measurement and a quantum simulator (like Qasm Simulator) to run the algorithm for a sufficient number of counts and show a histogram of the frequency of the measured states.
 

## Resources
- [Qiskit textbook](https://qiskit.org/textbook/ch-states/introduction.html)
- [Getting started with Qiskit](https://qiskit.org/documentation/tutorials/circuits/1_getting_started_with_qiskit.html)
- [Grover's Algorithm from textbook](https://qiskit.org/textbook/ch-algorithms/grover.html)
- [Youtube](https://www.youtube.com/watch?v=0RPFWZj7Jm0)
- [Dinner Party Problem](https://www.youtube.com/watch?v=ePr2MgQkqL0)
