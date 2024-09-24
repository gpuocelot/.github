i![alt text](gpuocelot.png)

NVIDIA GPU code could be emulated, and even translated to run on a different GPU architecture. If this fact does not surprise you, perhaps you have already heard about GPUOcelot!

GPUOcelot is a project developed by Gregory Diamos and Andrew Kerr et al at Georgia Institute of Technology. The development started in 2008, and seen the early days of GPU technology and LLVM compiler toolchain. Eventually, GPUOcelot even has become a backend of Optix raytracing engine for CPU fallback mode.

GPUOcelot re-targets GPU kernels originally intended for NVIDIA GPUs at PTX level. PTX is a special intermediate assembly, which connects CUDA language to NVIDIA GPU hardware. There are no other products that support PTX, but it is well-documented, and GPUOcelot bursts PTX support to theoretically any target LLVM has a backend for.

Obviously, GPUOcelot could do a lot of interesting and strange things in 2023, if it could work. The project was not maintained for quite some time. Now GPUOcelot has a second life! It supports the recent LLVM 15, Ubuntu 22.04 and modern NVIDIA CUDA Toolkit. 100% of the classical test suite is passing.

Check it, test it, learn from it, discuss, stargaze and do not forget to say thanks to Gregory and Andrew!
