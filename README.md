# VLI-Supercomputacion
Software para VLI Supercomputacion
Instrucciones para instalar el software:
Primero, deben tener el compilador en paralelo MPICH: 
https://www.mpich.org/documentation/guides/

Sistema Operativo:  Linux

Para compilar el software NBody:
make cpu-4th

Para ejecutar el solftware NBody:
mpirun -np 4 ./cpu-4th

