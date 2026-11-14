# ⚡ High Performance Computing — Laboratory Reports

A collection of **10 laboratory reports** from the **High Performance Computing (HPC)** course. Covers parallel programming paradigms, performance benchmarking, memory optimization, MPI communication, and GPU computing with CUDA.

---

## 📋 Lab Overview

| Lab | Topic | Key Technologies |
|-----|-------|-----------------|
| **Lab 1** | Pseudo-Random Number Generation | C, `rand()`, `srand()`, file I/O |
| **Lab 2** | Sparse Matrix Storage (CRS Format) | C, CRS arrays, validation |
| **Lab 3** | Sparse Matrix-Vector Multiplication (SpMV) | C, CRS kernel, dense vs sparse comparison |
| **Lab 4** | MPI Point-to-Point Communication | C, OpenMPI, `MPI_Wtime`, `mpirun` |
| **Lab 5** | Parallel SpMV with MPI | C, MPI_Bcast, MPI_Scatter, MPI_Gather |
| **Lab 6** | STREAM Benchmark & Memory Bandwidth | C, STREAM (Copy/Scale/Add/Triad), AMD Ryzen 7 |
| **Lab 7** | *(included in benchmark series)* | Performance analysis |
| **Lab 8** | Matrix-Vector Optimization Analysis | C, GCC `-O0` vs `-O3`, assembler comparison, cache locality |
| **Lab 9** | Computational Benchmarking (SpMV) | C, `CLOCK_MONOTONIC`, GFLOPS, memory bandwidth |
| **Lab 10** | CUDA Workload Distribution | CUDA C, `cudaGetDeviceProperties`, shared memory, 1D stencils |

---

## 🛠️ Technologies & Tools

<p>
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenMPI-3D6AA2?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/GCC-A42E2B?style=for-the-badge&logo=gnu&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/WSL-0a97f5?style=for-the-badge&logo=windows&logoColor=white" />
</p>

---

## 🔬 Topics Covered

- **Memory Optimization**: Compressed Row Storage (CRS) format for sparse matrices
- **Parallel Computing**: MPI (Message Passing Interface) for distributed computation
- **GPU Programming**: CUDA kernels, shared memory, device profiling
- **Performance Analysis**: GFLOPS measurement, memory bandwidth, STREAM benchmarks
- **Compiler Optimization**: Comparison of `-O0` vs `-O3` GCC flags, assembler-level analysis
- **Benchmarking Methodology**: High-resolution timing (`CLOCK_MONOTONIC`), statistical analysis

---

## 💻 Environment

| Component | Specification |
|---|---|
| **OS** | WSL2 (Ubuntu) on Windows |
| **CPU** | Intel Core i3-1115G4 / AMD Ryzen 7 7840HS |
| **RAM** | 8 GB |
| **GPU** | NVIDIA (CUDA-capable) |
| **Compiler** | GCC, NVCC |
| **MPI** | OpenMPI |

---

## 📁 Project Structure

```
hpc-labs/
├── Lab01_Random_Numbers.pdf
├── Lab02_Sparse_Matrix_CRS.pdf
├── Lab03_SpMV_Implementation.pdf
├── Lab04_MPI_Communication.pdf
├── Lab05_Parallel_SpMV_MPI.pdf
├── Lab06_STREAM_Benchmark.pdf
├── Lab08_Matrix_Vector_Optimization.pdf
├── Lab09_Computational_Benchmarking.pdf
├── Lab10_CUDA_Workload.pdf
└── README.md
```

---

## 🎓 Academic Context

| Field | Details |
|---|---|
| **Subject** | High Performance Computing |
| **Student** | Victoria Yolanda Sánchez Fernández |
| **Program** | B.Sc. Computer Engineering |

---

## 🧑‍💻 Author

**Victoria Sánchez** — Computer Engineering Student @ ULPGC
GitHub: [@yoqjs](https://github.com/yoqjs)
