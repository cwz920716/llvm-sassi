# llvm-sassi

A port of NVIDIA SASSI (https://github.com/NVlabs/SASSI) onto llvm with nvptx backend (https://llvm.org/docs/NVPTXUsage.html).
This librray supports static instrumentation of cuda applications using gpucc(llvm).

Before, this was tested on CUDA 8.0 with llvm 6.0, but it breaks at CUDA 9.0
due to some linking issue. I haven't got time to fix it so it may not work now.
