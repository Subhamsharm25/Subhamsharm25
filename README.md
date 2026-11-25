# Hi, I'm Subham Sharma 👋

**Research · Core systems engineering · DevOps & multi-cloud**

I build small, honest, fully verified systems — every repo here ships with tests, a reproducible pipeline, and a README that says exactly what is real and what is simulated. One new project lands on this profile **every day**.

---

## 🔬 Research

My research interest sits where **machine learning meets infrastructure**: making automated operations *verifiable* — control planes that can prove what they did, prediction with calibrated uncertainty instead of point guesses, and systems that stay safe under failure.

| Project | What it studies |
|---|---|
| [nexus-ops](https://github.com/Subhamsharm25/nexus-ops) | A verifiable, risk-aware agentic control plane for cloud-native CI/CD — code, experiments and results |
| [QuanGAT](https://github.com/Subhamsharm25/QuanGAT) | Federated graph attention network with quantum encodings for DNA mutation prediction |

Ongoing (private until submission): quantum-safe conformally calibrated control planes, reinforcement-learning release gating, energy-aware scheduling for wireless rechargeable sensor networks.

## ⚙️ Engineering highlights

| Project | Area | What it does |
|---|---|---|
| [cloudmirror](https://github.com/Subhamsharm25/cloudmirror) | Multi-cloud reliability | Quorum replication gateway across AWS S3, Azure Blob and GCS — integrity checks, self-repair, automated outage drills; Terraform + Helm + k3d + dual CI (Jenkins & GitHub Actions) |
| [tf-guardrails](https://github.com/Subhamsharm25/tf-guardrails) | Platform security | Policy gate for Terraform PRs on AWS/Azure/GCP — blocks public storage, open SSH/RDP, unencrypted DBs; SARIF output, expiring waivers, composite GitHub Action |

## 📅 Daily builds

One small, production-grade project a day — rotating three tracks: **A** DevOps/cloud · **B** research-grade experiments · **C** core systems building blocks. Every repo: unit tests, one `ci.py` driving both GitHub Actions and Jenkins identically, pinned non-root images, MIT license, honest limits.

| Date | Repo | Track | Problem |
|---|---|---|---|
| 2026-11-24 | [tf-guardrails](https://github.com/Subhamsharm25/tf-guardrails) | A | Risky Terraform changes reach production because reviews miss policy violations |
| 2026-11-23 | [cloudmirror](https://github.com/Subhamsharm25/cloudmirror) | A | A single cloud-storage outage can take down data access entirely |

## 🧰 Stack

`Python` · `Terraform` · `Kubernetes` / `Helm` / `k3d` · `Docker` · `GitHub Actions` · `Jenkins` · `AWS` · `Azure` · `GCP` · `Prometheus` · `PyTorch`

## 📐 How I work

- **No gap between elements** — every file in a repo is exercised by a CI stage; names match across code, compose, manifests and Terraform.
- **One pipeline, two runners** — a single `ci.py` holds every stage; GitHub Actions and Jenkins both just call it.
- **Honest READMEs** — emulated is labelled emulated; results tables only contain numbers that were actually produced.
