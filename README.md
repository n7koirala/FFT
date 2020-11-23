# FFT
This repo contains the implementations of serial and parallel version (using OpenMP) of Fast Fourier Transform in C.

## Serially
For the serial version, the program could be run using these commands:

$ gcc -o serialfft FFT_SERIAL.c -lm

$ ./serialfft

## Parallelly
For the parallel version, the number of threads needs to be specified after compilation:

$ gcc -o prallelfft -fopenmp FFT_OPENMP.c -lm

$ export OMP_NUM_THREADS=2

$ ./parallelfft

