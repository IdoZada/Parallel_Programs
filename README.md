
Parallal-Histogram

A project,calculate histogram of given array of numbers between 1-256 (Read from stdin) by using parallel programing.
There are two processes running using MPI where each process gets half of the array and compute his histogram with Cuda and OpenMP.
Finally merge the result into 1 complete array(root process take care of this by using MPI).
