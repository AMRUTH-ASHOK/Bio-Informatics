# DEBRUIJN STRING RECONSTRUCTION

## This is part of the bio-informatics course 
https://www.coursera.org/specializations/bioinformatics#instructors

## The algorithm followed in this method is clearly explained in the below videos
#### https://www.youtube.com/watch?v=xYHpuZLvB2s&t=1s
#### https://www.youtube.com/watch?v=6DI3SB7DyFY
#### https://www.youtube.com/watch?v=f-ecmECK7lw
#### https://www.youtube.com/watch?v=_x4IVlsw_q4


Brief: (k-1)mers are arranged as nodes in a graph, the edges follow a particular logic for its placement. This gives us a graph. The primary objective here is to find a eulerian path in the graph (if any) and use this path to reconstruct the String.

Note: There might be multiple eulerian paths in a given graph, hence multiple reconstructed strings are prevalent. Eulerian string reconstruction does not necessarily give a unique output. This is a drawback of this algorithm, and it is addressed in Paired Debruijn String Reconstruction methods.
