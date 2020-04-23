#cuda-stream (Executable only)
==========
cuda-stream: ELF 64-bit LSB executable, x86-64, version 1 (SYSV), dynamically linked (uses shared libs), for GNU/Linux 2.6.32, BuildID[sha1]=c5a46be43b98f7ea896786dbed6edcaa643d50cf, not stripped

cuda toolkit version 9.2
intel tools version 18

Measure memory transfer rates to/from global device memory on GPUs.
This benchmark is similar in spirit, and based on, the STREAM benchmark [1] for CPUs.

Unlike other GPU memory bandwidth benchmarks this does *not* include the PCIe transfer time.

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
