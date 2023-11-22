# OpenMPI-Programming
Understanding distributed computing fundamentals on OpenMPI


mv hello_world.cpp /home/mpi/cloud

mpicxx -o hello_world hello_world.cpp
mpirun -hostfile my_host ./hello_world
