# kernellab-cuda-optimization
Hand-written CUDA kernels for the operations that dominate deep learning: GEMM, softmax, layernorm, and attention. Each kernel is built up in steps, from a naive version to a tuned one, and compared against cuBLAS. Includes Nsight profiling results and notes on what limited each version and what fixed it.
