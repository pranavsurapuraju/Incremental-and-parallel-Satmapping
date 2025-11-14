This project is an implementation of a SAT-based quantum circuit mapper inspired by the paper:

Quantum Circuit Mapping Based on Incremental and Parallel SAT Solving
 Jiong Yang 
 Yaroslav A. Kharkov 
 Yunong Shi 
 Marijn J.H. Heule 
 Bruno Dutertre

Modern quantum processors have limited qubit connectivity, which requires inserting SWAP gates to bring qubits together.
This project uses Boolean SAT solving, incremental and parallel encoding techniques to minimize the number of SWAP gates while mapping quantum circuits to hardware topologies.

The repository includes an initial prototype implementation, experiments, and a Jupyter notebook demonstrating the mapping pipeline.
