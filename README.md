<div align="center">

# Ryan Levey

<a href="https://www.linkedin.com/in/ryan-levey/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn" /></a>
<a href="https://github.com/theryeguy92"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>

**Data Engineer & AI Technical Advisor — UCOR / U.S. Department of Energy**
**M.S. Computer Science, Vanderbilt University '25**

LLM evaluation frameworks, agent tracing, and OpenTelemetry-based observability. 8+ years in analytics
spanning ML, A/B testing, data engineering, and system design.

</div>

---

## Featured Projects

| Project | Language | Description |
|---------|:--------:|--------------|
| [**CachePotato**](https://github.com/theryeguy92/CachePotato) | C | Co-designed sparse (MoE) LLM engine that treats SSD, RAM, and CPU cache as one addressable memory space. Trains the router for memory locality, then serves a 736 MB model inside a 512 MB RAM budget. Benchmarked against dense GPT-2 under pre-registered success gates: **+149% throughput where the dense model doesn't fit**, and **42% less paging I/O** from locality-aware routing. Zero runtime dependencies. |
| [**vecmap**](https://github.com/theryeguy92/vecmap) | Python · CUDA | GPU-accelerated document similarity and knowledge-graph engine — **553M pairwise cosine scores/sec** (~12 ms on an RTX 5080). Custom CUDA kernels over a pybind11 bridge, thresholding into a sparse CSR graph, then BFS / PageRank / Dijkstra / MST to surface coverage gaps and critical nodes across document corpora. |
| [**llm-eval-harness**](https://github.com/theryeguy92/llm-harness-eval) | Python | Reproducible LLM evaluation framework: YAML or dataset-driven prompts, parallel multi-model runs, 5 evaluators (LLM-as-judge coherence / relevance / faithfulness, plus ROUGE-L and exact match), bootstrap 95% confidence intervals, pairwise comparison with documented position-swap debiasing, and per-call cost tracking. CI green. |
| [**Elio IDE**](https://github.com/theryeguy92/elio-ide) | TypeScript · Python | Browser-based IDE for writing and debugging AI agents, built around the **run trace** as the primary interface. Every LLM call, tool invocation, memory op, and agent handoff streams over WebSocket in real time; click a trace step and Monaco jumps to the source line. Next.js 14 + FastAPI. |
| [**PDF RAG App**](https://github.com/theryeguy92/PDF-LLM-Context-Injection-App) | Python · Terraform | Cloud-native PDF question-answering pipeline: upload and parse PDFs, store content in MySQL, query via an LLM service. Kafka Streams glue four Dockerized services across **Terraform-provisioned AWS infrastructure** (VPC, subnets, security groups, EC2). |

## Other Projects

| Project | Language | Description |
|---------|:--------:|--------------|
| [**NES Emulator**](https://github.com/theryeguy92/Java-NES-Emulator) | Java | Full Nintendo Entertainment System emulator — cycle-level CPU and PPU emulation. |
| [**Waffle House — Formal Verification**](https://github.com/theryeguy92/WaffleHouse-Magic-Marker-Project) | nuXmv · Z3 | Modeling the Waffle House "Magic Marker" plate-position ordering system as state machines, then proving its rules and combinations correct with formal verification (nuXmv model checking, Z3 solving). |
| [**HTB: Solar Labs**](https://github.com/theryeguy92/HTB-Solar-Lab) | — | Hack The Box writeup: Active Directory enumeration, password spraying, user pivoting, and privilege escalation. |
| [**HTB: Blurry**](https://github.com/theryeguy92/HTB_Blurry_Writeup/tree/main) | — | Hack The Box writeup: privilege escalation against the ClearML ML platform via CVE-2024-24590. |

---

## Technical Skills

<div align="center">

**Languages**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B" alt="Python" /> <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C" /> <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA" /> <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" /> <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" /> <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" /> <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />

**AI & Observability**

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" /> <img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white" alt="OpenTelemetry" /> <img src="https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Airflow" />

**Data & Cloud**

<img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge" alt="AWS" /> <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" alt="Snowflake" /> <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" /> <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka" /> <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />

**Web, Systems & Security**

<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" /> <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" /> <img src="https://img.shields.io/badge/RHEL-EE0000?style=for-the-badge&logo=redhat&logoColor=white" alt="RHEL" /> <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark" /> <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge" alt="Tableau" /> <img src="https://img.shields.io/badge/Z3-6B4FBB?style=for-the-badge" alt="Z3" />

</div>
