<div align="center">

# Sai Krishna Varanasi

### Senior C++ Systems Engineer · 8.5+ Years

**I build fast, concurrent, production-grade C++ systems on Linux, and I fix the bugs other people can't reproduce.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/varanasi-sai-krishna-997a7b1a0/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Krish1994-coder)
<!-- Add your email so recruiters can reach you in one click:
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:you@example.com)
-->

![C++](https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![GoogleTest](https://img.shields.io/badge/GoogleTest-4285F4?style=flat-square&logo=google&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)

</div>

---

## 💼 At a Glance

| | |
|---|---|
| **Role** | Senior C++ Systems Engineer |
| **Experience** | 8.5+ years across Web Content Management, FinTech, Telecom, and Embedded Systems |
| **Core strengths** | Modern C++ · Linux/POSIX · Multithreading · Performance Engineering · Storage Internals |
| **Known for** | Diagnosing crashes, races, and deadlocks in production · Making slow code fast · Writing code others can maintain |
| **Open to** | Senior / Lead C++ roles in systems, storage, databases, low-latency, and infrastructure |

---

## 🎯 What I Bring to a Team

**🔧 I ship production C++, not just prototypes.**
Eight-plus years of building, extending, and supporting C++ in real products across four industries, from feature work to on-call fixes.

**🐞 I'm the person you call when it's broken.**
Core dumps, memory corruption, race conditions, deadlocks. I work through them with GDB, Valgrind, and methodical root-cause analysis until the actual cause is found and fixed.

**⚡ I measure before I optimize.**
I profile CPU, memory, and lock contention to find real bottlenecks, then fix them in throughput- and latency-sensitive code paths.

**🧱 I understand what's under the abstraction.**
I've built a database engine, a key-value store, and a distributed data loader from scratch, so I know how storage, caching, and concurrency behave in practice.

**✅ I leave code better than I found it.**
TDD with Google Test and Mock, CI/CD with Jenkins, thorough code reviews, and designs grounded in SOLID and RAII.

<!-- 💡 TIP: Recruiters respond most to numbers. If you can, add 2–3 real results here, e.g.
- Reduced request latency by X% by ...
- Cut memory usage of <service> from X GB to Y GB
- Resolved a long-standing production crash affecting N customers
-->

---

## 🛠️ Technical Skills

| Area | Stack |
|---|---|
| **Modern C++** | C++11/14/17 · STL · RAII · Templates · Smart Pointers · Move Semantics · OOD · SOLID |
| **Systems** | Linux/Unix · POSIX · Processes · IPC · File Systems · FUSE · Daemons |
| **Concurrency** | Multithreading · Mutexes · Condition Variables · Thread Pools · Thread Safety |
| **Performance** | Profiling · CPU & Memory Analysis · Lock Contention · Throughput · Latency |
| **Networking** | TCP/IP · Sockets · Client/Server · TLS/SSL |
| **Storage** | B+ Trees · Key-Value Stores · Persistence · Transactions · Write-Ahead Logging |
| **Debugging** | GDB · Valgrind · Core Dumps · Race & Deadlock Analysis · RCA |
| **Delivery** | CMake · Google Test / Mock · Jenkins · CI/CD · Docker · Kubernetes · Git · TDD |

---

## 🚀 Featured Projects

Each project was built to go deep on one area of systems engineering.

| Project | What It Proves |
|---|---|
| 🗄️ **[TinyDB](https://github.com/Krish1994-coder/tinydb)** | I understand database internals end-to-end: storage engine, buffer pool, B+ tree indexing, transactions, WAL |
| ⚡ **[FastKVS](https://github.com/Krish1994-coder/fastkvs)** | I can design concurrent, high-throughput systems and back them with benchmarks |
| 🌐 **Distributed Data Loader** 🔒 | I can reason about partitioning, routing, batching, and correctness across nodes |
| 🔐 **[Weak Cipher Detector](https://github.com/Krish1994-coder/Weak-Cipher-Detection-Agent)** | I apply C++ to security problems (TLS configuration analysis) |
| 🔗 **[C++ SSL Client](https://github.com/Krish1994-coder/exasol-cpp-ssl-client)** | I work comfortably with secure networking and TLS client code |
| 📊 **[push_back vs emplace_back](https://github.com/Krish1994-coder/cpp-push-vs-emplace-benchmark)** | I validate performance claims with data instead of assumptions |

<details>
<summary><b>🔍 Project details (click to expand)</b></summary>

<br>

### 🗄️ [TinyDB](https://github.com/Krish1994-coder/tinydb): Relational Database Engine
A relational database engine built from scratch in C++17 to explore database internals and storage-engine design.

`C++17` `Storage Engine` `Buffer Pool` `B+ Tree` `Transactions` `WAL`

### ⚡ [FastKVS](https://github.com/Krish1994-coder/fastkvs): High-Performance Key-Value Store
A multithreaded key-value store with an LRU cache, persistence layer, thread pool, and benchmarking support.

`C++` `Concurrency` `Thread Pool` `LRU Cache` `Persistence` `Benchmarking`

### 🌐 Distributed In-Memory Data Storage & Loader
🔒 *Private repository, available on request*

A C++17 system that simulates a 1–5 node cluster in a single process:
- Deterministic hash-based partitioning with local and remote record routing
- Batched transport over a mock socket-style network layer
- Concurrent per-node loader and receiver threads
- Deterministic duplicate-key resolution
- End-to-end ownership and correctness verification, with unit tests

`C++17` `Distributed Systems` `Partitioning` `Concurrency` `Batching` `Verification`

### 🔐 [Weak Cipher Detection Agent](https://github.com/Krish1994-coder/Weak-Cipher-Detection-Agent): Hackathon Project
A scanning agent that detects weak TLS ciphers and outdated cryptographic configurations.

`C++` `Security` `TLS/SSL` `Cipher Analysis`

### 🔗 [Exasol C++ SSL Client](https://github.com/Krish1994-coder/exasol-cpp-ssl-client)
Explores secure SSL/TLS client-side communication in C++.

`C++` `SSL/TLS` `Networking` `Client/Server`

### 📊 [push_back vs emplace_back Benchmark](https://github.com/Krish1994-coder/cpp-push-vs-emplace-benchmark)
Measures when `emplace_back` actually beats `push_back`, and when it doesn't.

`C++` `STL` `Move Semantics` `Benchmarking`

</details>

<p align="right"><a href="https://github.com/Krish1994-coder?tab=repositories">→ See all repositories</a></p>

---

## 🌱 Currently Leveling Up

- **C++20/23:** concepts, ranges, coroutines, modules
- **Deeper systems work:** Linux internals, storage engines, distributed systems
- **AI-assisted engineering:** using AI for review, debugging, and research, while keeping the fundamentals sharp

---

## 📈 GitHub Stats

<div align="center">
<img src="./profile-summary-card-output/<theme-folder>/3-stats.svg" height="165" alt="GitHub Stats"/>
<img src="./profile-summary-card-output/<theme-folder>/2-most-commit-language.svg" height="165" alt="Top Languages"/>
</div>

---

<div align="center">

### 📬 Hiring for C++, systems, or performance work? Let's talk.

[![LinkedIn](https://img.shields.io/badge/Message_me_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/varanasi-sai-krishna-997a7b1a0/)

</div>
