<h1 align="center">sonx</h1>

<p align="center">
  <b>Reverse engineering · Windows internals · Exploitation</b><br>
  Building low-level security tooling and learning pwn in public.
</p>

<p align="center">
  <a href="https://sonx4444.github.io/">Blog</a>
</p>

---

I write tools that take Windows and PE internals apart and put them back together — kernel callbacks, hooks, PE rewriting, system instrumentation. Most of it starts as "how does this actually work?" and ends as something runnable.

### 🛠️ Projects

| Project | What it is | Stack |
|---|---|---|
| [**aegis**](https://github.com/sonx4444/aegis) | Windows kernel-mode EDR built from scratch — driver registers OS callbacks and streams events to a user-mode agent | C / WDK |
| [**apiscope**](https://github.com/sonx4444/apiscope) | API monitoring and interception framework that maps an import-free DLL, installs trampolines across multiple target DLLs, and streams structured events through shared memory | C++ |
| [**peforge**](https://github.com/sonx4444/peforge) | C++17 library for parsing and modifying PE files — bounded views, separate read/mutate APIs, code-cave discovery | C++ |
| [**exe2dll**](https://github.com/sonx4444/exe2dll) | Converts Windows PE executables into DLLs by patching headers and injecting an export directory into code caves | C++ |
| [**goosquery**](https://github.com/sonx4444/goosquery) | SQL-powered OS instrumentation for Windows, inspired by osquery | Go |
| [**CTFs**](https://github.com/sonx4444/CTFs) | rev / pwn / malware writeups, plus challenges I've authored for local events | Python / asm |

### 🧭 Currently

- Building **aegis** into a real kernel EDR, one telemetry source at a time — and writing it up on the [blog](https://sonx4444.github.io/).
- Grinding **pwn** (heap, ROP, kernel) and posting writeups as I go.

### 🔧 Working with

![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Assembly](https://img.shields.io/badge/x86--64_asm-525252?style=flat&logo=gnu&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Windows](https://img.shields.io/badge/Windows_internals-0078D6?style=flat&logo=windows&logoColor=white)

---

<p align="center">
  <sub>ᓚᘏᗢ</sub>
</p>
