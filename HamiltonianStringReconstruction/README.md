# HAMILTONIAN STRING RECONSTRUCTION

## This is part of the bio-informatics course 
https://www.coursera.org/specializations/bioinformatics#instructors

## The algorithm followed in this method is clearly explained in the below video
https://www.youtube.com/watch?v=bDj8TWG3NRM&t=5s

Brief: kmers are arranged as nodes in a graph, the edges follow a particular logic for its placement. This gives us a graph. The primary objective here is to find a hamiltonian path in the graph (if any) and use this path to reconstruct the String.

Note: There might be multiple hamiltonian paths in a given graph, hence multiple reconstructed strings are prevalent. Hamiltonian string reconstruction does not necessarily give a unique output. There is no efficient way to solve the hamiltonian path problem. These two are the 2 drawbacks of this algorithm, and are addressed in Debruijn, and Paired Debruijn String Reconstruction methods.
