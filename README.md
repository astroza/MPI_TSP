MPI_TSP
=======

Parallel TSP Solution using MPI (Sistemas Distribuidos 2014/1 @ UTalca)

Compiling
=======

* mpicc tsp.c -o tsp

with debug enabled

* mpicc -DENABLE_DEBUG tsp.c -o tsp

Usage
=======

* mpirun --np 4 ./tsp 4 inputs/matrix
