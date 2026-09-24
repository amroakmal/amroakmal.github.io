# Amr Akmal Abouelmagd

**PhD Student, Computer Science · HPC & GPU Systems Researcher · Software Engineer**

🔗 **Live portfolio → https://amroakmal.github.io/**

---

I chase one question: how do large-scale systems *actually* behave when you push them
to the edge? My research runs from **GPU architecture, partitioning, and power** and
**cross-vendor GPU hardware-counter mapping** on the AMD MI300A APU behind **LLNL's El
Capitan exascale supercomputer**, to **fault tolerance in HPC**, **KV-caching architecture
and performance**, and reshaping **MPI for the AI era** so it stays fault-tolerant and
keeps making strong progress under failure. I'm a **PhD student and Graduate Research
Assistant at Tennessee Tech**, advised by Prof. Anthony Skjellum, following a research
internship at **Lawrence Livermore National Laboratory**.

## Research interests

- GPU Architecture, Partitioning & Power
- Cross-Vendor GPU Performance Analysis & Hardware Counters
- Fault Tolerance in HPC Systems
- KV-Caching Architecture & Performance
- MPI for AI — fault-tolerant, strong progress
- Distributed Systems & Parallel Computing
- Systems Performance Analysis

## Education

- **Ph.D. in Computer Science** — Tennessee Technological University · *Aug 2026 – Present (expected Aug 2030)* · advised by Prof. Anthony Skjellum
- **M.S. in Computer Science** — Tennessee Technological University · GPA 4.0/4.0 · *completed Aug 2026*
- **B.S. in Computer Engineering** — Alexandria University, Faculty of Engineering · *2016 – 2021*

## Experience

**Tennessee Technological University** — Graduate Research Assistant *(Aug 2026 – Present)*
- PhD research advised by Prof. Anthony Skjellum: cross-vendor GPU performance analysis and hardware counters, fault tolerance in HPC, KV-caching architecture and performance, and fault-tolerant, strong-progress MPI for AI.

**Lawrence Livermore National Laboratory** — Graduate Research Intern, Computation Directorate *(2025 – 2026)*
- Systems-level research on the AMD MI300A APU: GPU runtime scheduling, dynamic power sharing, and heterogeneous memory behavior.
- Benchmarked RAJA Performance Suite kernels across **SPX / TPX / CPX** partitioning modes, surfacing up to **30% execution-time variance** across configurations.
- Investigated cross-vendor GPU hardware-counter mapping across the ROCm/HIP profiling stack (Caliper, Thicket, rocprofiler-sdk).
- Authored a peer-reviewed paper on MI300A partitioning, power, and performance (accepted at SCA/HPC Asia 2026), targeting optimization of LLNL's El Capitan exascale supercomputer.

**Incorta** — Software Engineer II → R&D Software Engineer → Graduate Student Intern *(2021 – 2024)*
- Optimized a distributed analytics platform on Kubernetes + ZooKeeper for enterprise-scale workloads.
- Delivered a **2× indexing speedup** and **7× query-latency reduction** on datasets exceeding 1 billion records.
- Designed an internal caching layer that cut cloud object-storage I/O and cost; raised average CPU utilization from **40% to 85%**.

## Selected publications

*(9 papers · 5 first-author · full list on the [live site](https://amroakmal.github.io/#publications))*

1. **A. A. Abouelmagd**, et al. *[ProTools @ SC'26 — title to be finalized].* **ProTools, SC'26 — to appear.**
2. *[OpenCCL poster — title to be finalized]* (incl. **A. A. Abouelmagd**). **Poster, SC'26 — to appear.**
3. **A. Abouelmagd**, D. Boehme, S. Brink, J. Burmark, M. McKinsey, A. Skjellum, O. Pearce. *GPU Partitioning, Power, and Performance of the AMD MI300A.* **SCA/HPC Asia 2026.**
4. **A. A. Abouelmagd**, O. Pearce, S. Brink, M. McKinsey, D. Boehme, J. Burmark, B. Ryujin, T. Scogland, A. Skjellum. *Using Hardware Metrics to Understand Performance of RAJA Suite Kernels in Different GPU Modes on MI300A.* **Poster, SC'25 — Top 5 Finalist, Graduate Student Research Competition.**
5. S. Yang, X. Yao, G. Nansamba, **A. A. Abouelmagd**, A. Skjellum, M. Herbordt. *Load Imbalance in HPC Applications: Improved Profiling and New Ways to Use Wasted Cycles.* **IEEE HPEC 2025.**
6. E. Namugwanya, G. Nansamba, **A. A. Abouelmagd**, A. Skjellum. *A Survey of Optimization Approaches for MPI Alltoall and MPI Alltoallv.* **SAI Computing Conference 2025.**
7. **A. A. Abouelmagd**, A. Hilal. *Leveraging the Power of AI and Social Interactions to Restore Trust in Public Polls.* **CSCI 2025.**
8. **A. A. Abouelmagd**, A. Hilal. *Emerging Paradigms for Securing Federated Learning Systems.* **IEEE GCAIoT 2025.**
9. P. H. Chen, A. Bali, S. Yang, P. Haghi, C. Knox, B. Li, **A. A. Abouelmagd**, A. Skjellum, M. Herbordt. *Cycle-Stealing in Load-Imbalanced HPC Applications.* **IEEE HPEC 2024 — Outstanding Student Paper Award.**

## Projects

- **CUDA Parallel Softmax** *(C++, CUDA)* — Optimized softmax kernel using shared memory and block-level reduction; throughput scaled via memory coalescing and parallel row-wise processing.
- **Distributed Key-Value Store** *(C++)* — Leader-coordinated store with auto-partitioning, live rebalancing, and Bully-algorithm leader election for zero-data-loss failover.
- **BusTub Database Engine** *(C++)* — Buffer-pool manager with page-replacement policies and a thread-safe LRU-K eviction algorithm. *(CMU course project; solution repo kept private per course policy.)*

## Skills

- **Languages:** C/C++, Python, Java, Go
- **Parallel & HPC:** MPI, CUDA, Kokkos, RAJA Performance Suite
- **Profiling & HPC tooling:** HIP, ROCm, Caliper, Thicket, Nsight Compute, rocprofiler-sdk, Benchpark, Spack
- **Systems & Infra:** Kubernetes, Docker, ZooKeeper, MySQL
- **Tools:** Linux, Git, CMake, Makefile

## Awards

- **Top 5** — Graduate Student Research Competition, ACM/IEEE SuperComputing (SC'25)
- **Outstanding Student Paper Award** — IEEE HPEC 2024
- **10th place, AlexCPC** — qualified for the Egyptian Collegiate Programming Contest (2018)
- Cloud DevOps Nanodegree — Udacity

## Contact

- 📧 **Email:** aabouelma42@tntech.edu
- 🎓 **Google Scholar:** https://scholar.google.com/citations?user=FJQIUp4AAAAJ&hl=en
- 💼 **LinkedIn:** https://linkedin.com/in/amroakmal
- 💻 **GitHub:** https://github.com/amroakmal
- 📄 **Résumé:** add `resume.pdf` to the repo root to enable the résumé link on the site

---

### About this repository

This repo hosts my personal portfolio site — a single self-contained `index.html`
(no build step) served by GitHub Pages. The empty `.nojekyll` file tells Pages to
serve the HTML as-is instead of running a Jekyll build. To update the site, edit the
text in `index.html` directly.
