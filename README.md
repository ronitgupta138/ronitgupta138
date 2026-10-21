<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0b0e,100:00f2fe&height=210&section=header&text=Ronit%20Gupta&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Systems%20and%20Distributed%20Backend%20Engineer&descAlignY=62&descAlign=50" width="100%"/>

<a href="https://github.com/ronitgupta138">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=2800&pause=1200&color=00F2FE&center=true&vCenter=true&multiline=false&width=800&height=50&lines=Systems+and+Distributed+Backend+Engineer;Building+Lean%2C+High-Throughput+Engines;Linux+Internals+%E2%80%A2+Concurrency+%E2%80%A2+Low-Latency;Hand-Crafted+Code+from+First+Principles" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ronitgupta138)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ronitgupta138)
[![Portfolio](https://img.shields.io/badge/Portfolio-0891b2?style=for-the-badge&logo=firefox&logoColor=white)](https://ronitgupta138.github.io)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ronitgupta138@gmail.com)
[![Location](https://img.shields.io/badge/Location-Kolkata%2C%20India-0891b2?style=for-the-badge&logo=google-maps&logoColor=white)](https://www.google.com/maps/place/Kolkata,+West+Bengal)

</div>

---

### ⚡ Live Workstation Snapshot

```bash
ronit@workstation:~$ aero doctor --summary
──────────────────────────────────────────────────────────────────────────
  OS            ::  Aero Linux v1.5.0-Pulsar [Kernel 7.0 / Rolling Edge / Wayland]
  Host / CPU    ::  AMD Ryzen 5 5600H (6C/12T @ 4.2GHz / Low-Latency P-State)
  Memory        ::  15.3 GB Physical [7.5 GB Dynamic zRAM ZSTD In-Memory Compression]
  Education     ::  CSBS @ Netaji Subhash Engineering College (2023–2027)
  Core Stack    ::  Rust, Java (Loom/Virtual Threads), TypeScript, Node.js, C, PostgreSQL, Redis
  Philosophy    ::  "Zero Bloat • First-Principles Depth • Hand-Crafted Code"
──────────────────────────────────────────────────────────────────────────
```

---

### 📦 Featured Engineering Systems & Infrastructure

#### ⚡ 1. Distributed Engines & High-Throughput Systems
* **⚡ [AvioStream](https://github.com/ronitgupta138/AvioStream)** — *Closed-Loop Autonomous Fleet Telemetry & Predictive Maintenance Platform.* Built in Java 21 Loom (>48,000 msgs/s virtual thread ingestion buffer) with embedded ONNX runtime edge inference (0.014ms), dual ML (Isolation Forest + LightGBM asymmetric NASA PHM loss), and sub-15ms deterministic SAP PM / IBM Maximo CMMS work-order dispatch.
* **⚡ [Apex-Matching-Engine](https://github.com/ronitgupta138/Apex-Matching-Engine)** — *Ultra-Low Latency Continuous Double Auction Order Book.* Price-time priority (FIFO) execution engine built in Java 21 Loom, delivering in-memory L2 market depth updates, concurrent order matching, and real-time STOMP WebSocket feeds exceeding 50,000 ops/sec.
* **🇮🇳 [Bharat-Spatial-Engine](https://github.com/ronitgupta138/Bharat-Spatial-Engine)** — *National-Scale Geospatial Hierarchy & Proximity Query Engine.* Sub-millisecond reverse geocoding and radius proximity search across India's 650,000+ census settlements and MDDS codes. 2D geographic KD-Tree with spherical Haversine pruning and transliteration-tolerant Indic trigram search, clocking 38,400+ QPS with 2.09ms p99 latency in Java 21 Loom.
* **⚡ [Vectra-Core](https://github.com/ronitgupta138/Vectra-Core)** — *In-Memory Vector Search Engine & HNSW Graph Index.* High-dimensional approximate nearest neighbor (ANN) retrieval in Java 21 Loom virtual threads. 8-bit scalar quantization (SQ8) with 75% RAM reduction, filtered hybrid vector search, and verified 16,900+ QPS with 0.28ms median latency.

#### 🤖 2. Autonomous Agent Infrastructure & Memory (Rust & Crates.io)
* **⚡ [BurnRate](https://github.com/ronitgupta138/BurnRate)** — *Terminal HUD, Hard Spend Caps & Cache Guard for Coding Agents.* Never wake up to surprise $40 Claude Code or Cursor bills. Pure-Rust zero-overhead reverse proxy enforcing hard budget circuit breakers (`HTTP 402`), byte-level prompt-cache invalidation linting, token-cost optimal cascade routing, multi-agent quotas, sliding-window velocity brakes, native MCP server, and Prometheus export. Published on Crates.io (`burnrate-agent`).
* **⚡ [Agent-2PC](https://github.com/ronitgupta138/Agent-2PC)** — *Heterogeneous Two-Phase Commit (2PC) & WAL Engine for AI Agents.* Eliminates dirty repository state, broken syntax, and hallucinated rollbacks across autonomous agent tool pipelines. Rust engine featuring crash-consistent binary Write-Ahead Log (`fsync` + CRC32), isolated scratchspaces, deterministic rollbacks, and drop-in Model Context Protocol (MCP) server support.
* **⚡ [Agent-MemGC](https://github.com/ronitgupta138/Agent-MemGC)** — *The Linter, Cache-Layout Optimizer & Generational Garbage Collector for AI Agent Instructions.* Audit, clean, and deduplicate `CLAUDE.md`, `AGENTS.md`, and `.cursorrules`. Detects dead file path references, resolves conflicting directives, eliminates prompt-cache-busting volatile prefixes, and auto-fixes context bloat in <15ms. Native MCP server published on Crates.io (`agent-memgc`).
* **⚡ [Local-Jev](https://github.com/ronitgupta138/Local-Jev)** — *100% Offline, Zero-Cost Drop-In Alternative to TypeSafe Jev System One Decisions.* Sub-18ms local CPU decision engine (`Choice`, `Score`, `Noul`, `Route`). Single-forward-pass logit extraction, SIMD quantized linear layer, speculative cascade routing, contextual bandit feedback, zero API keys, and seamless Axum REST server published on Crates.io.

#### 🐧 3. Operating Systems, Cloud & Full-Stack Platforms
* **⚡ [Aero-Linux](https://github.com/ronitgupta138/aero-linux)** — *Ultra-Lean Developer OS & Native Systems Suite.* Sub-350MB idle footprint, dynamic zRAM (ZSTD) memory optimization, 59 native zero-terminal GTK3 developer applications, 133/133 unit tests, eBPF kernel tracing, ephemeral KVM microVMs, automated Debian package builds (`.deb`), and [live web portal ↗](https://ronitgupta138.github.io/aero-linux/).
* **⚡ [FinFlow-Core](https://github.com/ronitgupta138/FinFlow-Core)** — *Enterprise Banking & Financial Aggregation REST Platform.* [[Live API ↗](https://finflow-core.onrender.com)] Built on Spring Boot 3.3, Java 17, Spring Security 6 (stateless JWT authentication), PostgreSQL 16, and Docker. Features multi-tenant isolation, automated scheduled market data ingestion, custom JPQL financial aggregation, and an offline UPI mesh settlement engine (indexed on [XERJ Corpus Hub ↗](https://hub.xerj.org/contributors/ronitgupta138)).
* **🎙️ [Vox-Intel-Engine](https://github.com/ronitgupta138/Vox-Intel-Engine)** — *Multi-Modal Speech Telemetry & Acoustic DSP AI Engine.* Built with Python 3.11 and FastAPI for real-time speech analytics. Extracts pitch fundamental frequencies via autocorrelation DSP, spectral energy distribution via FFT, and lexical delivery metrics (WPM, filler word density, type-token ratio).
* **⚡ [Dine-Luxe](https://github.com/ronitgupta138/Dine-Luxe)** — *High-Concurrency POS & Reservation Engine.* [[Live on Vercel ↗](https://dine-luxe.vercel.app)] Real-time table lifecycle management, optimistic locking against double-booking, sub-millisecond cache invalidation, and transactional consistency built with TypeScript, Node.js, Express, Prisma ORM, and PostgreSQL.

---

### 🌐 Merged Upstream Open-Source Contributions

| Repository | Ecosystem / Subsystem | Contribution Scope | Status |
| :--- | :--- | :--- | :---: |
| **[`redis/lettuce#3963`](https://github.com/redis/lettuce/pull/3963)** | Java / Core Redis Driver | Forwarded raw `ByteBuffer` errors in `MultiOutput` to preserve per-element error tolerance in transactions (#3960) | `MERGED` |
| **[`ratatui/ratatui#2850`](https://github.com/ratatui/ratatui/pull/2850)** | Rust / Terminal Systems | Guarded `Buffer::set_stringn` against out-of-bounds panics on degenerate terminal viewports (#2810) | `MERGED` |
| **[`redisson/redisson#7390`](https://github.com/redisson/redisson/pull/7390)** | Java / Distributed Storage | Added `RBatch.getMap` variants accepting custom `MapOptions` (#6096) | `MERGED` |
| **[`xerj-org/xerj#1994 & #1995`](https://github.com/xerj-org/xerj/pull/1994)** | AI Indexing & Search Engine | Contributed `Vectra-Core` in-memory HNSW reference corpus & signed in-repo CLA | `MERGED` |
| **[`lucide-icons/lucide#4957`](https://github.com/lucide-icons/lucide/pull/4957)** | TypeScript / Frontend Framework | Exported `__iconData` and `__iconNode` per-icon geometry modules in `@lucide/svelte` (#4936) | `MERGED` |

---

### 🛠️ Tech Stack & Tooling

<div align="center">

#### 💻 Languages & Systems
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Java](https://img.shields.io/badge/Java%2021%20Loom-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

<br/>

#### 🚀 Backend Architecture & Frameworks
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=for-the-badge&logo=hono&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma%20ORM-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![GTK3](https://img.shields.io/badge/GTK%203%20%2F%20GJS-4A90E2?style=for-the-badge&logo=gnome&logoColor=white)

<br/>

#### 🗄️ Databases, In-Memory Caching & Cloud Infrastructure
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

### 📊 Real-Time GitHub Activity & Metrics

<div align="center">

<a href="https://github.com/ronitgupta138">
  <img src="https://hits.sh/github.com/ronitgupta138.svg?style=flat-square&label=Profile+Views&color=0891b2&labelColor=0a0b0e" alt="Profile Views" />
</a>
&nbsp;
<a href="https://github.com/ronitgupta138">
  <img src="https://img.shields.io/github/followers/ronitgupta138?style=flat-square&label=Followers&labelColor=0a0b0e&color=0891b2&logo=github&logoColor=00f2fe" alt="Followers" />
</a>

<br/>

<a href="https://committers.top/india">
  <img src="https://user-badge.committers.top/india_public/ronitgupta138.svg" alt="committers.top badge" />
</a>

<br/>

<a href="https://github.com/ronitgupta138">
  <img src="https://github-analytics-incog.vercel.app/api?username=ronitgupta138&theme=github_dark" alt="GitHub Analytics Dashboard" width="100%" />
</a>

</div>

---

<div align="center">

<p><i>"Simplicity is prerequisite for reliability." — Edsger W. Dijkstra</i></p>

</div>
