<div align="center">

<p>
  <img src="assets/brand/singularity-cloud-network-logo.png" alt="Singularity Cloud Network logo" width="150" />
</p>

# Singularity Cloud Network Research

**Working papers and technical preprints for the Singularity Cloud Network.**

Decentralized AI compute, verifiable inference, confidential hardware, tokenized compute markets, and agent-native cloud infrastructure.

[![Status](https://img.shields.io/badge/status-working%20papers-black)](#papers)
[![License](https://img.shields.io/badge/license-CC--BY--4.0-blue)](LICENSE)
[![Lab](https://img.shields.io/badge/lab-EventHorizon%20Labs-111111)](https://github.com/EventHorizon-Labs/eh-labs-research)
[![Research](https://img.shields.io/badge/research-ehlabs.xyz%2Fresearch-orange)](https://www.ehlabs.xyz/research)

<p>
  <a href="https://www.ehlabs.xyz/research"><img src="assets/brand/ehlabs-logo.png" alt="EventHorizon Labs logo" width="72" /></a>
  &nbsp;&nbsp;&nbsp;
  <img src="assets/brand/singularity-logo.png" alt="Singularity logo" width="72" />
</p>

</div>

---

## Scope

This repository is the focused publication surface for the **Singularity Cloud Network** paper series. It is separate from the broader [EventHorizon Labs research hub](https://github.com/EventHorizon-Labs/eh-labs-research), which tracks pillars, experiments, and research-roadmap work across the lab.

Research home: **[ehlabs.xyz/research](https://www.ehlabs.xyz/research)**

The series studies one question from multiple angles:

> How can AI compute become an open, community-owned, verifiable, confidential, and agent-native cloud network?

## Papers

| # | Paper | Theme | Status | PDF | Source |
| --- | --- | --- | --- | --- | --- |
| SCN-001 | **Tokenized Compute Markets** | Market mechanism for self-growing AI compute capacity | Working paper v0.1 | [PDF](papers/2026-tokenized-compute-markets/releases/tokenized-compute-markets-whitepaper.pdf) | [TeX](papers/2026-tokenized-compute-markets/source/paper.tex) |
| SCN-002 | **Singularity Grid** | Verifiable, confidential, OpenAI-compatible inference across independent nodes | Forthcoming | - | - |
| SCN-003 | **Singularity Hive Mind** | Sharded large-model serving across many local/cloud nodes | Forthcoming | - | - |

## Current Release

### Tokenized Compute Markets

**A Self-Growing Mechanism for Community-Owned, Verifiable, Confidential, and Agentic AI Compute**

The first paper introduces Tokenized Compute Markets, a mechanism that couples capital formation, physical infrastructure deployment, and AI inference into a self-growing loop. Trading activity funds real machines through a Hardware Fund, while inference remains priced in a stable unit and settled through cluster tokens.

Key topics:

- mechanism design for community-owned compute
- tokenized settlement and batched operator payouts
- hardware-funded capacity growth
- confidential AI inference and TEE trust tiers
- agentic market creation and autonomous compute participation
- failure modes: velocity, wash markets, demand/supply reflexivity, and liquidity fragmentation

Read:

- [Paper README](papers/2026-tokenized-compute-markets/)
- [Rendered PDF](papers/2026-tokenized-compute-markets/releases/tokenized-compute-markets-whitepaper.pdf)
- [GitHub release](https://github.com/EventHorizon-Labs/singularity-cloud-network-research/releases/tag/tokenized-compute-markets-v0.1)

## Repository Layout

```text
papers/
  2026-tokenized-compute-markets/
    README.md
    metadata.yml
    releases/
      tokenized-compute-markets-whitepaper.pdf
    source/
      paper.tex
docs/
  series-roadmap.md
```

## Citation

Use the repository-level [CITATION.cff](CITATION.cff) or the paper-specific metadata file. Until a DOI is assigned, cite the GitHub release or paper directory.

## License

Unless a paper directory states otherwise, text and papers in this repository are released under the Creative Commons Attribution 4.0 International License. Code snippets, scripts, and machine-readable metadata are released under the MIT License.

---

<div align="center">

**EventHorizon Labs**  
Research toward decentralized, verifiable, confidential, and agentic cloud infrastructure.

</div>
