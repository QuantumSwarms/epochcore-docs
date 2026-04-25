# epochcore-docs

![docs](https://img.shields.io/badge/docs-mkdocs--material-blue) ![license](https://img.shields.io/badge/license-Apache--2.0-green) ![status](https://img.shields.io/badge/status-public--reference-informational)

Public documentation & architecture overview for the **EpochCore** platform — covering **D-KaP** (Decentralized Knowledge as Pixels), **EpochOS**, **EpochPay**, **EpochCoverage**, and the **QuantumSwarms** agent fabric.

> This repository contains only public-facing architecture, specifications, and integration guides. Proprietary implementation details live in private EpochCore repositories.

---

## What is EpochCore?

EpochCore is a quantum-anchored AI agent platform that unifies:

- **D-KaP** — Decentralized Knowledge as Pixels, a tensor-addressable knowledge substrate.
- **EpochOS** — the orchestration runtime for swarm-scale autonomous agents.
- **EpochPay** — a programmable settlement layer for agent-to-agent and agent-to-human commerce.
- **EpochCoverage** — compliance, audit, and risk primitives for regulated deployments.
- **QuantumSwarms** — the agent fabric integrating D-Wave quantum sampling and PQC-safe integrity.

## Documentation Map

| Area | Path | Description |
|------|------|-------------|
| Platform overview | `docs/overview.md` | High-level architecture |
| D-KaP | `docs/dkap.md` | Knowledge-as-pixels primitives |
| EpochOS | `docs/epochos.md` | Agent orchestration runtime |
| EpochPay | `docs/epochpay.md` | Settlement + payments |
| EpochCoverage | `docs/epochcoverage.md` | Compliance + audit |
| QuantumSwarms | `docs/quantumswarms.md` | Agent fabric + quantum integration |

## Related Public Repositories

- [`epochcore-dkap-spec`](https://github.com/QuantumSwarms/epochcore-dkap-spec) — D-KaP specification
- [`epochcore-sdk`](https://github.com/QuantumSwarms/epochcore-sdk) — Public Python client SDK
- [`watsonx-orchestrate-hydro`](https://github.com/QuantumSwarms/watsonx-orchestrate-hydro) — Hydro agent reference for watsonx Orchestrate
- [`quantum-watermark-sbom`](https://github.com/QuantumSwarms/quantum-watermark-sbom) — Quantum watermark + SBOM scheme

## Build Locally

```bash
pip install mkdocs-material
mkdocs serve
```

## License

Apache-2.0 © EpochCore / QuantumSwarms
