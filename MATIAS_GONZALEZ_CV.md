# Matias Ezequiel Gonzalez

**Systems Engineer → High-Performance Computing & Quantitative Analysis**

Santiago de Compostela, Galicia, Spain · EU Passport · [github.com/maezgonz](https://github.com/maezgonz) · [linkedin.com/in/maezgonz](https://www.linkedin.com/in/maezgonz)

---

## Profile

Systems engineer with **17 years in mission-critical infrastructure and telecommunications** — from electrical power systems for radio bases to Core Network architecture (IMS, VoLTE, 5G SBA) — including **12 years at Telefónica Argentina** deploying, operating and optimizing mobile networks (2G/3G/4G/5G) across core and access with Ericsson, Huawei, ZTE and IBM equipment.

Currently pursuing an **MSc in High-Performance Computing at Universidade de Santiago de Compostela** (BEME merit scholarship, Xunta de Galicia), running parallel workloads on **CESGA FinisTerrae-3**. That background taught me to reason about latency, throughput and reliability at scale — the same principles I now apply to parallel computing and quantitative finance.

**Open to work:** HPC Engineer · Quantitative Developer · Python Developer · Infrastructure/SRE — EU, on-site/hybrid/remote.

---

## Selected Work — github.com/maezgonz

**[hpc-parallel-algorithms](https://github.com/maezgonz/hpc-parallel-algorithms)** — Parallel algorithms in C, benchmarked on CESGA FinisTerrae-3 (Intel icc 2021.3, Intel MPI, InfiniBand):

- OpenMP Monte Carlo kernel: **17.6× speedup on 64 cores** (10⁹ samples), per-thread PCG RNG
- **GBM engine: 2.66M paths/s** (10⁹ paths, antithetic variates) — validated against the closed-form Black-Scholes distribution to **6 significant digits**
- Hybrid MPI+OpenMP Laplace solver across **2 physical nodes** with halo exchange
- MPI ping-pong benchmark: **2.8 µs inter-node RTT / 12.2 GB/s**
- Scaling-limit analysis with roofline framing; 12 MPI lab exercises from MSc coursework

**[quant-trading-models](https://github.com/maezgonz/quant-trading-models)** — Quantitative research in Python with an HPC mindset:

- Vectorized Monte Carlo (GBM), Black-Scholes pricing with Greeks, implied volatility (Newton-Raphson + bisection)
- Risk metrics: VaR, CVaR, Sharpe, Sortino, beta, drawdowns; quantstats HTML tear sheets
- One fully worked strategy workflow: SMA crossover backtest with no lookahead bias
- **HPC bridge**: the C engine's output cross-validated against the NumPy kernel
- 24 unit tests, ruff lint, CI on every push

**[telco-network-automation](https://github.com/maezgonz/telco-network-automation)** — Carrier-grade automation tooling (stdlib-only, CI-tested):

- Parallel TCP fleet prober (bounded thread pool, latency percentiles)
- Configuration drift detection against golden baselines with security-pattern flagging

**[telco-engineering-handbook](https://github.com/maezgonz/telco-engineering-handbook)** — Knowledge base (7 reference documents, standards-based):

- 3GPP KPI definitions, alarm correlation (ITU-T X.733), controller stress-testing methodology, EMF/RNI analysis (ICNIRP), MML command patterns, spectrum refarming, core network evolution — published as a mkdocs site

---

## Experience

### Telefónica Argentina — 12 years

**RF/O-RAN Network Engineer, Operations & Systems Specialist** · Jun 2021 – Aug 2026
Remote

- Orchestrated the 4G→5G transition: gNodeB swap/integration toward Service-Based Architectures
- Implemented network slicing (NSI) and RAN intelligence (RIC) frameworks for ultra-low-latency QoS flows
- Led EPC→5GC modernization oversight (AMF/SMF/UPF) within NFV/Cloud environments
- Executed end-to-end redundancy and stress testing on next-gen controllers, holding 99.9% availability during massive traffic surges

**RAN Network Engineer, Systems Support** · Jun 2017 – Jun 2021
Buenos Aires, Argentina

- Led large-scale migrations of RNC/BSC legacy systems to modern high-capacity platforms, enhancing national throughput
- L1/L2 hardware/software integration across global vendors; commissioning and ATP coordination achieving 100% QoS compliance
- Fault management, configuration management, spectrum refarming

**Core Network Engineer Support** · Dec 2015 – Jun 2017
Argentina

- Managed mission-critical core NEs (vUSN, vUGW, blade clusters), ensuring subscriber data integrity (HSS/HLR)
- Led VoLTE/VoIP implementation and Core IMS deployment; ATM-to-IP migrations in MGWs reducing backbone latency

**RNI Measurement Engineer** · Aug 2014 – Dec 2015
Argentina

- Statistical inference (frequentist/Bayesian) on RF probe data → high-precision immission/emission models
- Certified reports and histograms for regulatory approval; EMF hot-spot identification through spatial analysis

### Geo Solutions — RAN Network Engineer · Nov 2012 – Aug 2014
Argentina

- National-level operator benchmarking (Nemo tools) with statistical post-processing of KPI datasets
- Actix Analyzer/Spotlight data mining; network monitoring dashboards translating RF metrics into business intelligence

### Sistemas Energéticos S.A. — Electrical Technician · Jan 2009 – Nov 2011
Argentina

- Maintenance of critical electrical infrastructure (UPS, 48V power systems, rectifiers) for power stations and radio bases

---

## Education

| Degree | Institution | Dates |
|---|---|---|
| **MSc in High-Performance Computing** (BEME merit scholarship) | Universidade de Santiago de Compostela | Sep 2026 – Sep 2027 |
| **BASc/BSc equivalent — Licentiate in Data Science** | Universidad de la Ciudad de Buenos Aires | Aug 2025 – Jul 2026 |
| **BASc/BSc equivalent — Licentiate in Digital Technologies** | Universidad de la Ciudad de Buenos Aires | Mar 2024 – Jul 2025 |
| **BTech, Telecommunications Engineering** | Universidad Tecnológica Nacional | Mar 2021 – Feb 2024 |
| **Associate, Computer Systems Networking** | IFTS 19 | Aug 2006 – Dec 2009 |

---

## Skills

| Domain | Technologies |
|---|---|
| HPC & Parallel Computing | C, C++, OpenMP, MPI, Slurm, CUDA (in progress), Linux |
| Quant & Data | Python (pandas, NumPy, SciPy, scikit-learn), Monte Carlo, Black-Scholes, risk metrics, time series |
| Telco & Infra | 2G/3G/4G/5G RAN & Core, IMS/VoLTE, NFV/OpenStack, Kubernetes, Docker |
| Cloud & Security | Azure (AZ-900, DP-100, SC-200), Power BI, KQL/Sentinel |
| Practice | CI/CD (GitHub Actions), git, testing, performance analysis |

---

## Certifications (selected)

- Programa de Especialización en Finanzas Cuantitativas — Bolsa de Comercio de Rosario (2025)
- Programa de Especialización en Trading de Derivados — Bolsa de Comercio de Rosario (2025)
- Microsoft Security Operations Analyst (SC-200) — Microsoft (2023)
- Designing and Implementing a Data Science Solution on Azure (DP-100) — Microsoft (2023)
- 5G Masterclass: Architectures, NR RAN, Core and Call Flows — Udemy (2023)
- Ericsson 5G NSA & SA Architecture — Ericsson (2023)
- OpenStack and NFV Telco Cloud — Telefónica (2023)
- Analysing Data with Power BI (DA-100) — Microsoft (2022)
- Azure Fundamentals (AZ-900) — IT College (2021)

---

## Languages

Spanish (native) · English (B2/C1 — Dexway Academy)
