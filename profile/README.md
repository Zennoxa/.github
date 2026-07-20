<div align="center">

# 🛡️ Zennoxa Shield

### Find, prioritize & fix code security risks — one scan, every layer.

*The all-in-one security scanner you run yourself. Your code never leaves.*

[![OWASP Benchmark](https://img.shields.io/badge/OWASP%20Benchmark%20v1.2-%231%20%C2%B7%2092.8%25%20precision-16a34a)](https://github.com/Zennoxa/shield/blob/main/docs/EVIDENCE.md)
[![Latest release](https://img.shields.io/github/v/release/Zennoxa/shield?label=CLI&color=4f46e5)](https://github.com/Zennoxa/shield/releases/latest)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/Zennoxa/shield/blob/main/LICENSE)
![Platforms](https://img.shields.io/badge/platforms-macOS%20%C2%B7%20Linux%20%C2%B7%20Windows-informational)

[**Website**](https://zennoxa.com) · [**CLI**](https://github.com/Zennoxa/shield) · [**Docs**](https://zennoxa.com/docs) · [**Guide**](https://zennoxa.com/guide) · [**Benchmarks**](https://github.com/Zennoxa/shield/blob/main/docs/EVIDENCE.md) · [**Issues**](https://github.com/Zennoxa/shield/issues)

</div>

---

Most scanners bury you in findings. **Shield runs SAST, secrets, dependency, container, IaC and CI/CD checks in one pass**, then ranks every issue **0–100 by real-world risk** (CVSS + EPSS + CISA KEV + code reachability) — so the exploitable stuff rises and the noise sinks.

### 🧩 One scan, every layer

| 🔍 SAST | 🔑 Secrets | 📦 Dependencies | 🐳 Containers | 🏗️ IaC | ⚙️ CI/CD |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 14 languages | 26 patterns | OSV + SBOM | Dockerfile / images | Terraform · K8s · CFN | pipeline risks |

### 📊 Proof, not claims

<div align="center"><img src="profile/benchmark.svg" alt="OWASP Benchmark v1.2 — Shield +0.450 Benchmark Score at 92.8% precision" width="560"></div>

- **[OWASP Benchmark v1.2](https://owasp.org/www-project-benchmark/)** (2,740 labelled Java tests): Shield scores **+0.450 at 92.8% precision** — reproducible; competitor scores are OWASP&#8217;s own published figures.
- On a real Node project: Shield detected **all 9** known-vulnerable advisories — reproduce and compare with any tool.
- Every number is reproducible — and we publish the weak spots too → **[see the full evidence →](https://github.com/Zennoxa/shield/blob/main/docs/EVIDENCE.md)**

### 🔒 Why Zennoxa

Every big scanner is SaaS — your source code goes to *their* cloud. Shield is **self-hosted and offline**: all-in-one coverage with enterprise-grade precision, and **your code never leaves your machine.** Free during beta.

### 🚀 Get started

```bash
# scan any repo — SAST + secrets, no account needed
shield scan .
```
```yaml
# ...or add it to CI in 3 lines
- uses: Zennoxa/shield@v0.1.0
```

<div align="center">

**[🌐 zennoxa.com](https://zennoxa.com)** · **[💻 Download the CLI](https://github.com/Zennoxa/shield)** · **[📊 Benchmarks](https://github.com/Zennoxa/shield/blob/main/docs/EVIDENCE.md)**

</div>
