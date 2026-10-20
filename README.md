<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Terminal: Aditya Trivedi, compiler engineer on the ARM LLVM team at Qualcomm, Hyderabad" />

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditya-trivedi-a30b70259/)
[![Portfolio](https://img.shields.io/badge/Portfolio-111111?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-adit-six.vercel.app)
[![GSoC Blog](https://img.shields.io/badge/GSoC_'25_Blog-4285F4?style=flat-square&logo=google&logoColor=white)](https://gsoc-blogs-5vgw.vercel.app)
[![Forge](https://img.shields.io/badge/Forge-3fb950?style=flat-square&logo=github&logoColor=white)](https://github.com/adit4443ya/forge)

</div>

<br>

I'm a compiler engineer on the ARM LLVM team at Qualcomm. My job is getting machines to run code faster, then checking that the speedup is real.

<br>

## What I work on

- **LLVM backends: AArch64.** I read IR and assembly until one of us blinks. NEON, SVE, SME.
- **MLIR and ClangIR.** I lower things one dialect at a time, upstream and in public, with reviewers.
- **OpenMP, MPI and GPU offload.** Teaching N cores to argue productively. In Google Summer of Code '25 I built OpenMP 6.0 infrastructure and GPU offloading for [LFortran](https://github.com/lfortran/lfortran).
- **HPC research.** Parallel graph algorithms, four publications. Graphs are matrices in denial, but BIG data indeed.
- **Fortran.** Older than my dependencies, faster than my opinions.

**Tools:** `C++` · `LLVM` · `MLIR` · `AArch64 asm` · `OpenMP` · `MPI` · `CUDA` · `Fortran`

<br>

<div align="center">

<img src="./assets/compiler_bug.svg" width="100%" alt="Flowchart: is it a compiler bug? If it persists at -O0, it's your bug. If sanitizers fire, it's undefined behavior. Otherwise reduce it, bisect the pass and file it upstream." />

</div>

<br>

## Known issues

```console
$ man aditya | grep -A10 "KNOWN ISSUES"

  - asks "what was the baseline?" at parties
  - says "it's memory-bound" a lot. is right about as often as anyone
  - has opinions on phase ordering and nobody to share them with
  - will tell you your loop didn't vectorize because of the if-condition.
    his own didn't either. we're fine.
  - found out sanitizers can quietly stop the vectorizer. filed the
    upstream issue. is not proud of how long it took.
  - considers printf() a debugger for people who trust themselves
  - believes Fortran was fast in 1957 and still is. cope.
```

<br>

<div align="center">

<img src="./assets/benchmark.svg" width="100%" alt="Bar chart: a noisy laptop run shows 3.20x, a cleaner run shows 0.92x, a properly controlled run shows the real 1.04x" />

</div>

<br>

## Side quest: Forge

**[Forge](https://github.com/adit4443ya/forge)** is a practice gym for compiler, systems and low-latency engineers.

- **120 problems and 64 guided labs** covering compilers, systems and performance work.
- **Hints, patterns and solutions are timed.** They unlock only after you've had a real go, and Forge remembers what you peeked at.
- **A market-making game**, because why not.

[![Open Forge](https://img.shields.io/badge/Forge-open_the_gym-3fb950?style=for-the-badge&logo=github&logoColor=white)](https://github.com/adit4443ya/forge)

<br>

## Contribution graph

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/adit4443ya/adit4443ya/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/adit4443ya/adit4443ya/output/github-contribution-grid-snake.svg" />
  <img alt="Snake eating my GitHub contribution graph" src="https://raw.githubusercontent.com/adit4443ya/adit4443ya/output/github-contribution-grid-snake.svg" width="100%" />
</picture>

<br>

## Say hi

Want to talk about vectorizers, AArch64 codegen, OpenMP or a benchmark you don't quite trust? Message me on [LinkedIn](https://www.linkedin.com/in/aditya-trivedi-a30b70259/).

<br>

<div align="center">

*measure twice, optimize once.*

</div>
