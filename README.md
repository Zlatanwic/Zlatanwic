<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=3000&pause=1000&color=4EC9B0&center=true&vCenter=true&random=false&width=600&lines=Hey%2C+I'm+Kuo+Li+%F0%9F%91%8B;Systems+Hacker+%7C+AI+Infra+Builder;Rust+%E2%9D%A4%EF%B8%8F+RISC-V+%E2%9D%A4%EF%B8%8F+CUDA" alt="Typing SVG" />
</h1>

<p align="center">
  <em>CS Undergrad @ Tongji University · Building systems software that makes AI go brr</em>
</p>

<p align="center">
  <a href="mailto:rodebiau9320@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/Zlatanwic"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

---

### 🧬 About Me

I'm a third-year CS undergrad at **Tongji University**, obsessed with the boundary where **systems programming meets AI infrastructure**. I write OS kernels in Rust, optimize CUDA kernels for LLM inference, and think a lot about how memory hierarchies shape the performance of modern AI workloads.

When I'm not hacking on systems code, I'm probably watching **Manchester City** ⚽ or reading about distributed systems.

---

### 🔬 Research Interests

`AI Systems` · `LLM Inference Optimization` · `KV Cache / Paged Attention` · `Memory & Cache Management` · `Operating Systems & Runtime` · `High-Performance Computing` · `RISC-V`



---

### 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

#### NovaOS 🦀
**Rust · RISC-V64 · POSIX-Compatible Kernel**

A from-scratch monolithic kernel for RISC-V64 built in Rust (`no_std`/`no_main`):
- 35 Linux-compatible syscalls (`fork`, `execve`, `mmap`, `pipe`...)
- Preemptive scheduling, ELF loader, process management
- Buddy allocator, Sv39 page tables, VirtIO-blk, Ext4 read-only FS
- Safe/Unsafe layered architecture with `#[deny(unsafe_code)]` on core modules
- **77/80** functional tests passing

</td>
<td width="50%" valign="top">

#### [SemantiCache](https://github.com/Zlatanwic/SemantiCache-block) 🧠
**Python · PyTorch · Transformers · Qwen2.5-3B · CUDA**

Semantics-aware KV cache eviction for long-context LLM inference:
- Custom token-by-token decode prototype with `KVCacheManager` (no `model.generate()`)
- Eviction policy fusing cumulative attention, head entropy, query relevance & factual signals
- Role protection, recent window & block-wise contiguous retention
- **100%** accuracy on 90 standard tests, **93.3%** on 90 adversarial tests

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Paged KV Cache CUDA Kernels](https://github.com/Zlatanwic/Paged-KV-Cache-CUDA-Kernel-Optimization-for-LLM-Decoding) ⚡
**CUDA C++ · PyTorch C++ Extension · Nsight Compute**

High-performance paged attention kernels for LLM decode:
- Fused paged attention kernel: **2.0–3.7×** speedup over PyTorch baseline
- Memory throughput: **331 GB/s** (~94% of theoretical peak)
- FP16 KV cache variant: **2× memory saving**, up to **1.71×** additional speedup

</td>
<td width="50%" valign="top">

#### Distributed FS for ML Training 📂
**C++ · FUSE · I/O Pattern Analysis · Cache**

Internship @ SJTU DDST Lab — Optimizing file systems for PyTorch training I/O:
- Profiled read size distributions, file access frequencies & syscall overhead
- Built FUSE-based passthrough prototype with path resolution cache & negative cache
- Reduced metadata lookup overhead in high-frequency access patterns

</td>
</tr>
</table>

---

### 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white"/>
  <img src="https://img.shields.io/badge/C/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/RISC--V-283272?style=flat-square&logo=riscv&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
</p>

**Systems & Architecture:** Linux Kernel, Distributed Systems, Concurrency, Process/Memory Management, Page Tables, Syscalls, ELF, File Systems

**AI Systems / Perf:** CUDA C++, PyTorch, Transformers, vLLM, KV Cache, Paged Attention, Nsight Compute

**Tooling:** Git, CMake, C++/CUDA Extension Dev, Vite/Vue

---

### 🏆 Honors

| Award | Event | Date |
|-------|-------|------|
| 🥇 **National First Prize** (Team Rank #1) | Global Campus AI Algorithm Challenge | Dec 2025 |
| 🥈 **International Silver Medal** | iGEM (International Genetically Engineered Machine) | Oct 2025 |

**English:** IELTS 7.0 · CET-6 571

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Zlatanwic&show_icons=true&theme=material-palenight&hide_border=true&bg_color=0d1117&title_color=4EC9B0&icon_color=4EC9B0&text_color=c9d1d9" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Zlatanwic&layout=compact&theme=material-palenight&hide_border=true&bg_color=0d1117&title_color=4EC9B0&text_color=c9d1d9" width="37%" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Zlatanwic&theme=github_dark" width="90%" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Zlatanwic&theme=github_dark&utcOffset=8" width="44%" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Zlatanwic&theme=github_dark" width="44%" />
</p>

---

<p align="center">
  <em>"The gap between theory and practice is larger in practice than in theory."</em>
</p>
