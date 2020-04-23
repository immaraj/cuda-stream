#cuda-stream (Executable only)
==========

Measure memory transfer rates to/from global device memory on GPUs.
This benchmark is similar in spirit, and based on, the STREAM benchmark [1] for CPUs.

Unlike other GPU memory bandwidth benchmarks this does *not* include the PCIe transfer time.

There are multiple implementations of this benchmark in a variety of programming models.
Currently implemented are:
  - OpenCL
  - CUDA
  - OpenACC
  - OpenMP 3 and 4.5
  - Kokkos
  - RAJA
  - SYCL

This code was previously called GPU-STREAM.

Website
-------
[uob-hpc.github.io/BabelStream/](https://uob-hpc.github.io/BabelStream/)

Usage
-----

Drivers, compiler and software applicable to whichever implementation you would like to build against is required.

==========

Measure memory transfer rates to/from global device memory on GPUs.
This benchmark is similar in spirit, and based on, the STREAM benchmark [1] for CPUs.

Unlike other GPU memory bandwidth benchmarks this does *not* include the PCIe transfer time.

This code was previously called GPU-STREAM.

Built from Code written at the following website
-------
[uob-hpc.github.io/BabelStream/](https://uob-hpc.github.io/BabelStream/)

Usage
-----
AT the Unix command line type ./cuda-stream

Drivers, compiler and software applicable to whichever implementation you would like to build against is required.

