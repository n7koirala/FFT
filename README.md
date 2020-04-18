# FFT
This repo contains the implementations of serial and parallel version (using OpenMP) of Fast Fourier Transform in C.

For the serial version, the program could be run using the commands in the BASH shell:

$ gcc -o serialfft FFT_SERIAL.c -m

$ ./serialfft


For the parallel version, the number of threads needs to be specified after compilation:

$ gcc -o prallelfft -fopenmp FFT_OPENMP.c -lm

$ export OMP_NUM_THREADS=2

$ ./parallelfft

