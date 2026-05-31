# 🖥️ CPU Architecture Mastery

<p align="center">
  <b>Master CPU Architecture from ISA → Microarchitecture → Modern Processor Design</b><br>
  A complete roadmap for understanding how processors execute instructions, manage memory, optimize performance, and secure computation.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-CPU_Architecture-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Level-Beginner_to_Advanced-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-Computer_Architecture-blue?style=for-the-badge" />
  <img src="https://img.shields.io/github/stars/Srivathsan98/CPU-Architecture-Mastery?style=for-the-badge" />
</p>

---

## 🧠 About

**CPU Architecture Mastery** is a structured learning system designed to help you:

✔ Understand how processors execute instructions

✔ Learn modern CPU microarchitecture

✔ Master caches and memory hierarchies

✔ Understand pipelines and branch prediction

✔ Learn performance optimization techniques

✔ Explore multicore systems and cache coherence

✔ Understand processor security vulnerabilities

✔ Learn modern CPU design principles

---

## 🗺️ Roadmap Overview

```mermaid
flowchart LR

A[ISA Fundamentals]
--> B[Pipelines]

B --> C[Branch Prediction]

C --> D[Out-of-Order Execution]

D --> E[Superscalar Architectures]

E --> F[Integer Arithmetic]

F --> G[Floating Point]

G --> H[Caches]

H --> I[Memory Hierarchy]

I --> J[Cache Coherence]

J --> K[Memory Models]

K --> L[SIMD]

L --> M[Virtual Memory]

M --> N[Compiler Optimization]

N --> O[Power Management]

O --> P[CPU Security]

P --> Q[Trusted Execution]

Q --> R[Modern CPU Design]
```

---

## 🌐 GitHub Pages

Link to GitHub Page - https://srivathsan98.github.io/CPU-Architecture-Mastery/CPU-Mastery-Tracker.html

---

## 📚 Learning Modules

### 📐 ISA Fundamentals

* RISC vs CISC
* RISC-V
* ARM
* x86
* Instruction Encoding
* ABI
* Calling Conventions

### 🔄 Classic Pipelines

* IF
* ID
* EX
* MEM
* WB
* Hazards
* Forwarding
* Pipeline Stalls

### 🌿 Branch Prediction

* Static Prediction
* Dynamic Prediction
* BTB
* RAS
* Tournament Predictors
* TAGE

### 🔀 Out-of-Order Execution

* Tomasulo Algorithm
* Reservation Stations
* ROB
* Register Renaming
* Speculative Execution

### ⚡ Superscalar & VLIW

* Multiple Issue
* ILP
* SMT
* Hyper-Threading
* VLIW
* EPIC

### 🧮 Integer Arithmetic Units

* Adders
* Multipliers
* Dividers
* Barrel Shifters
* Carry Propagation

### 🔢 Floating Point Architecture

* IEEE 754
* FPU Design
* Rounding Modes
* Denormals
* FMA
* Numerical Precision

### 💾 Cache Architecture

* Direct Mapped
* Set Associative
* Replacement Policies
* Write Policies
* Cache Hierarchies

### 🔮 Memory Hierarchy & Prefetching

* DRAM
* Memory Controllers
* Hardware Prefetchers
* Software Prefetching
* MLP
* MSHR

### 🔗 Cache Coherence

* MSI
* MESI
* MOESI
* MESIF
* False Sharing
* Directory Protocols

### ⚖️ Memory Consistency Models

* Sequential Consistency
* TSO
* Relaxed Models
* Memory Barriers
* C++ Memory Model

### 📦 SIMD & Vector Processing

* SSE
* AVX
* AVX-512
* NEON
* RISC-V Vector Extension
* Auto Vectorization

### 🖥️ Virtual Memory & TLB

* Page Tables
* MMU
* TLB
* Huge Pages
* ASID
* IOMMU

### ⚙️ Compiler & CPU Co-Design

* Loop Unrolling
* Software Pipelining
* LTO
* PGO
* Binary Optimization

### 🔋 Power Management

* DVFS
* Turbo Boost
* C-States
* P-States
* Power Gating
* Thermal Management

### 🛡️ CPU Security

* Spectre
* Meltdown
* MDS
* Side Channels
* Retpoline
* KPTI

### 🔐 Trusted Execution

* Intel SGX
* AMD SEV
* ARM TrustZone
* TPM
* Secure Boot
* Attestation

### 🌍 Multicore Architecture

* Shared Memory
* NUMA
* Synchronization
* Scalability
* Interconnects

### 🏗️ Processor Design

* Front-End Design
* Back-End Design
* Execution Units
* Floorplanning
* Tradeoffs

### 🚀 Modern CPU Architectures

* Intel Core
* AMD Zen
* ARM Cortex
* Apple Silicon
* RISC-V Processors

### 🧠 Performance Analysis

* perf
* VTune
* uProf
* LLVM MCA
* Top-Down Analysis

### ⚡ High Performance Computing

* Throughput Optimization
* Memory Optimization
* Vectorization
* Parallel Computing

### 🔬 Silicon & Physical Design

* Timing Closure
* Power Analysis
* Clock Trees
* Physical Constraints

### 🔧 Hardware Verification

* Simulation
* Formal Verification
* Coverage Analysis
* Validation

### 📡 Processor Interconnects

* Ring Bus
* Mesh Networks
* NoC
* Coherent Fabrics

### 🤖 Accelerator Architectures

* GPUs
* NPUs
* TPUs
* DSPs
* AI Accelerators

### ☁️ Server Processors

* Xeon
* EPYC
* NUMA Systems
* Virtualization

### 📱 Mobile Processors

* ARM SoCs
* big.LITTLE
* Efficiency Cores
* Mobile Optimization

### 🏆 Advanced CPU Research

* Speculative Architectures
* Near-Memory Computing
* Chiplets
* Future CPU Trends

### 🎯 CPU Architecture System Design

* End-to-End Processor Design
* Tradeoff Analysis
* Real-World Architectures

---

## 🛠️ Projects (Hands-On)

| Project | Level | Description |
|----------|----------|-------------|
| 🔄 Pipeline Simulator | Beginner | Simulate a 5-stage pipeline |
| 📐 ISA Emulator | Beginner | Build a simple ISA interpreter |
| 💾 Cache Simulator | Intermediate | Model cache behavior and misses |
| 🌿 Branch Predictor Simulator | Intermediate | Compare prediction algorithms |
| 🔀 Tomasulo Simulator | Advanced | Out-of-order execution engine |
| 📦 SIMD Optimization Suite | Advanced | Optimize workloads using SIMD |
| 🖥️ Virtual Memory Simulator | Advanced | Simulate TLB and page tables |
| 🛡️ Side Channel Lab | Expert | Explore Spectre-style concepts |
| 🚀 Performance Analysis Toolkit | Expert | Build CPU benchmarking tools |
| 🏗️ Mini CPU Design Project | Expert | Design a complete processor |

---

## 📁 Project Structure

```bash
cpu-architecture-mastery/
│
├── 01-isa-fundamentals/
├── 02-pipelines/
├── 03-branch-prediction/
├── 04-out-of-order-execution/
├── 05-superscalar/
├── 06-integer-arithmetic/
├── 07-floating-point/
├── 08-cache-architecture/
├── 09-memory-hierarchy/
├── 10-cache-coherence/
├── 11-memory-models/
├── 12-simd/
├── 13-virtual-memory/
├── 14-compiler-codesign/
├── 15-power-management/
├── 16-cpu-security/
├── 17-trusted-execution/
├── 18-multicore/
├── 19-processor-design/
├── 20-modern-cpus/
├── 21-performance-analysis/
├── 22-high-performance-computing/
├── 23-silicon-design/
├── 24-hardware-verification/
├── 25-interconnects/
├── 26-accelerators/
├── 27-server-processors/
├── 28-mobile-processors/
├── 29-advanced-research/
├── 30-system-design/
├── projects/
└── README.md
```

---

## 🧰 Recommended Tools

| Tool | Purpose |
|--------|---------|
| perf | Linux CPU Profiling |
| Intel VTune | Performance Analysis |
| AMD uProf | CPU Profiling |
| LLVM MCA | Microarchitecture Analysis |
| Compiler Explorer | Assembly Inspection |
| objdump | Disassembly |
| GDB | Debugging |
| QEMU | CPU Emulation |
| gem5 | Architectural Simulation |
| Verilator | Hardware Simulation |

---

## 🎯 Goals

* 🖥️ Understand how CPUs actually work
* ⚡ Optimize software for modern processors
* 💾 Master memory hierarchy behavior
* 🔍 Analyze performance bottlenecks
* 🔒 Understand CPU security vulnerabilities
* 🏗️ Learn processor design principles
* 🚀 Think like a CPU architect

---

## 📈 Progress Tracker

* [ ] ISA Fundamentals
* [ ] Pipelines
* [ ] Branch Prediction
* [ ] Out-of-Order Execution
* [ ] Superscalar Architectures
* [ ] Integer Arithmetic
* [ ] Floating Point
* [ ] Cache Architecture
* [ ] Memory Hierarchy
* [ ] Cache Coherence
* [ ] Memory Consistency
* [ ] SIMD Processing
* [ ] Virtual Memory
* [ ] Compiler Co-Design
* [ ] Power Management
* [ ] CPU Security
* [ ] Trusted Execution
* [ ] Multicore Architecture
* [ ] Processor Design
* [ ] Modern CPUs
* [ ] Performance Analysis
* [ ] HPC
* [ ] Silicon Design
* [ ] Verification
* [ ] Interconnects
* [ ] Accelerators
* [ ] Server CPUs
* [ ] Mobile CPUs
* [ ] Advanced Research
* [ ] CPU System Design

---

## 🏆 End Goal

By the end of this roadmap, you should be able to:

✅ Read and understand processor documentation

✅ Analyze assembly efficiently

✅ Optimize software for modern CPUs

✅ Understand cache and memory behavior

✅ Debug performance bottlenecks

✅ Understand processor security

✅ Build CPU simulators

✅ Understand modern processor design

✅ Think like a CPU architect

---

## 🤝 Contributing

Want to improve this roadmap?

1. Fork the repo
2. Create a branch
3. Submit a Pull Request

---

## ⭐ Support

If this helped you:

👉 Star the repo

👉 Share with others

👉 Contribute projects & improvements

---

## 📜 License

MIT License

---

<p align="center">
Built with 🖥️ + ⚡ + 💾 + 🔬 + curiosity
</p>