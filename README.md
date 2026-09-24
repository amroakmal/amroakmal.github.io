# Amr Akmal Abouelmagd

**PhD Student, Computer Science · HPC & AI Systems Researcher · Software Engineer**

🟢 **Open to Summer 2027 internships** in HPC & AI systems · 📧 aabouelma42@tntech.edu

🔗 **Live portfolio → https://amroakmal.github.io/**

---

I work on the systems software behind large-scale HPC and AI: **fault tolerance**,
**KV-cache architecture and performance**, and **MPI and collective communication for AI**
that keep making progress, even under failures. I'm a PhD student at Tennessee Tech,
advised by Prof. Anthony Skjellum. Previously, I researched **GPU performance** on the
AMD MI300A (El Capitan's APU) and NVIDIA H100 at **Lawrence Livermore National Laboratory**,
and spent 2.5 years building production distributed systems at **Incorta**.

## Recent news

- **Sep 2026** — First-author paper *Deriving Vendor-Agnostic GPU Metrics from AMD MI300A and NVIDIA H100 Hardware Counters* accepted at the ProTools workshop at SC'26.
- **Sep 2026** — OpenCCL poster, proposing an open standard that unifies collective communication libraries (\*CCLs), accepted at SC'26.
- **Aug 2026** — Completed my M.S. at Tennessee Tech (4.0 GPA) and my LLNL research internship; started my PhD as a Graduate Research Assistant with Prof. Anthony Skjellum.

## Research interests

- Fault Tolerance in HPC Systems
- KV-Cache Architecture & Performance
- MPI & Collective Communication for AI — fault-tolerant, strong progress
- Distributed Systems & Parallel Computing
- Systems Performance Analysis
- GPU Performance — partitioning, power & cross-vendor hardware counters

## Experience

**Tennessee Technological University** — Graduate Research Assistant, advised by Prof. Anthony Skjellum *(Aug 2026 – Present)*
- Research on fault tolerance in HPC systems, KV-cache architecture and performance, and MPI for AI: communication that survives failures and makes strong progress.
- Contributing to **OpenCCL**, a proposed open standard and reference implementation that unifies collective communication libraries (\*CCLs) for performance, portability, and productivity; co-author of the SC'26 poster.

**Lawrence Livermore National Laboratory** — Graduate Research Intern, Computation Directorate *(Jan 2026 – Aug 2026)*
- Derived **vendor-agnostic GPU performance metrics** from AMD MI300A and NVIDIA H100 hardware counters, enabling like-for-like comparison across vendors; first-author paper accepted at the ProTools workshop at SC'26.
- Collected and analyzed hardware counters using Caliper, Thicket, rocprofiler-sdk, and Nsight Compute, with Benchpark and Spack for reproducible experiments.

**Lawrence Livermore National Laboratory** — Graduate Research Intern, Computation Directorate *(May 2025 – Aug 2025)*
- Designed and ran benchmarking experiments on the AMD MI300A APU across **SPX / TPX / CPX** partitioning modes using RAJA Performance Suite kernels, surfacing up to **30% execution-time variance** between configurations.
- Conducted systems-level analysis of GPU runtime scheduling, dynamic power sharing, and heterogeneous memory behavior.
- First-author paper accepted at SCA/HPC Asia 2026, targeting optimization of LLNL's El Capitan exascale supercomputer; **Top 5 Finalist** in the SC'25 Graduate Student Research Competition.

**Incorta** — Software Engineer II · R&D Software Engineer · Graduate Student Intern *(Aug 2021 – Feb 2024)*
- Delivered a **2× indexing speedup** and **7× query-latency reduction** on datasets exceeding 1 billion records in a distributed analytics platform built on Kubernetes and ZooKeeper, improving SLA compliance.
- Raised average CPU utilization from **40% to 85%** by resolving execution bottlenecks, reducing cluster over-provisioning.
- Designed an internal caching layer that cut cloud object-storage I/O and infrastructure cost with no hardware changes.
- Improved monitoring and telemetry, reducing incident MTTR across microservices.

## Publications

*9 publications · 5 first-author*

1. **A. A. Abouelmagd**, M. McKinsey, D. Boehme, S. Brink, O. Pearce. *Deriving Vendor-Agnostic GPU Metrics from AMD MI300A and NVIDIA H100 Hardware Counters.* **ProTools Workshop @ SC'26 — to appear.**
2. A. Skjellum, P. Bangalore, T. Hines, K. Humphrey, J. Martin, **A. A. Abouelmagd**, R. Shipley, R. Bisht, Z. Nine. *OpenCCL: A Proposed Open Standard and Reference Implementation Unifying \*CCLs for Performance, Portability, and Productivity.* **Poster, SC'26 — to appear.**
3. **A. Abouelmagd**, D. Boehme, S. Brink, J. Burmark, M. McKinsey, A. Skjellum, O. Pearce. *GPU Partitioning, Power, and Performance of the AMD MI300A.* **SCA/HPC Asia 2026.**
4. **A. A. Abouelmagd**, O. Pearce, S. Brink, M. McKinsey, D. Boehme, J. Burmark, B. Ryujin, T. Scogland, A. Skjellum. *Using Hardware Metrics to Understand Performance of RAJA Suite Kernels in Different GPU Modes on MI300A.* **Poster, SC'25** — 🏅 Top 5 Finalist, Graduate Student Research Competition.
5. S. Yang, X. Yao, G. Nansamba, **A. A. Abouelmagd**, A. Skjellum, M. Herbordt. *Load Imbalance in HPC Applications: Improved Profiling and New Ways to Use Wasted Cycles.* **IEEE HPEC 2025.**
6. E. Namugwanya, G. Nansamba, **A. A. Abouelmagd**, A. Skjellum. *A Survey of Optimization Approaches for MPI Alltoall and MPI Alltoallv.* **SAI Computing Conference 2025.**
7. **A. A. Abouelmagd**, A. Hilal. *Leveraging the Power of AI and Social Interactions to Restore Trust in Public Polls.* **CSCI 2025.**
8. **A. A. Abouelmagd**, A. Hilal. *Emerging Paradigms for Securing Federated Learning Systems.* **IEEE GCAIoT 2025.**
9. P. H. Chen, A. Bali, S. Yang, P. Haghi, C. Knox, B. Li, **A. A. Abouelmagd**, A. Skjellum, M. Herbordt. *Cycle-Stealing in Load-Imbalanced HPC Applications.* **IEEE HPEC 2024** — 🏅 Outstanding Student Paper Award.

## Education

- **Ph.D. in Computer Science** — Tennessee Technological University, Cookeville, TN *(Aug 2026 – Present; expected Aug 2030)*. Advised by Prof. Anthony Skjellum.
- **M.S. in Computer Science** — Tennessee Technological University *(Jan 2024 – Aug 2026)* · GPA 4.0 / 4.0
- **B.S. in Computer Engineering** — Alexandria University, Faculty of Engineering, Egypt *(Sep 2016 – Jun 2021)*

## Selected projects

- **Distributed Key-Value Store** (C++) — Leader-coordinated store with auto-partitioning and live rebalancing; Bully-algorithm failover for zero data loss; multithreaded reads with mutexes and atomics.
- **BusTub Database Engine** (C++) — Buffer-pool manager with page-replacement policies and a thread-safe LRU-K eviction algorithm (CMU course project).
- **CUDA Parallel Softmax** (C++, CUDA) — Shared-memory, block-level-reduction softmax kernel with memory coalescing and parallel row-wise processing.

## Skills

- **Languages:** C/C++, Python, Java, Go
- **Parallel & GPU programming:** MPI, CUDA, HIP, ROCm, Kokkos
- **Performance analysis:** Caliper, Thicket, Nsight Compute, rocprofiler-sdk, hardware counters
- **Benchmarking & reproducibility:** RAJA Performance Suite, Benchpark, Spack, CMake
- **Distributed systems & infra:** Kubernetes, Docker, ZooKeeper, MySQL
- **Developer tools:** Linux, Git, Makefile

## Awards

- 🏅 **Top 5**, Graduate Student Research Competition — ACM/IEEE SuperComputing (SC'25), 2025
- 🏅 **Outstanding Student Paper Award** — IEEE HPEC 2024
- **10th Place**, AlexCPC — qualified for ECPC (Egyptian Collegiate Programming Contest), 2018
- **Cloud DevOps Nanodegree** — Udacity

## Contact

- 📧 aabouelma42@tntech.edu
- 🎓 [Google Scholar](https://scholar.google.com/citations?user=FJQIUp4AAAAJ&hl=en)
- 💼 [LinkedIn](https://www.linkedin.com/in/amroakmal/)
- 💻 [GitHub](https://github.com/amroakmal)

---

### About this repository

This repository hosts my personal portfolio website, served by GitHub Pages at https://amroakmal.github.io/.
The site is a single self-contained `index.html` (no build step, no dependencies); `og-image.png` is the preview
image shown when the link is shared on LinkedIn, Slack, or email; and the empty `.nojekyll` file tells GitHub Pages
to serve the files exactly as they are.
