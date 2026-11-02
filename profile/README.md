# 🛣️ izon446-lab

**Small, verified pull requests — shipped by humans and agents, proven at the head SHA.**

[![OpenLane](https://img.shields.io/badge/flagship-openlane-2ea44f)](https://github.com/izon446-lab/openlane)
[![ProofSpec](https://img.shields.io/badge/spec-proofspec-blue)](https://github.com/izon446-lab/proofspec)
[![License: MIT](https://img.shields.io/badge/license-MIT-yellow)](#-license)
[![Good first issues](https://img.shields.io/badge/good%20first%20issues-welcome-orange)](https://github.com/search?q=org%3Aizon446-lab+label%3A%22good+first+issue%22+state%3Aopen&type=issues)

We are a small open-source lab building tooling for an agent-assisted workflow where every change is tiny, scoped, and backed by runtime Proof — not just green checkmarks.

## 🔧 What we build

- **Agent desk** — an orchestrator that turns briefs into small, reviewable PRs.
- **Proof tooling** — a contract and schema for runtime evidence tied to a commit.
- **CI guards** — Actions that reject evidence that doesn't match the head SHA.
- **Brief linting** — catch vague task briefs before an agent burns time on them.
- **Agent Skills** — scaffolds for reusable, shareable skill packs.
- **Upstream care** — forks of tiny utilities we depend on, kept healthy.

## 📦 Repositories

| Repo | What it is |
|---|---|
| [**openlane**](https://github.com/izon446-lab/openlane) | Open-source agent desk for small, verified PRs — the flagship. |
| [**proofspec**](https://github.com/izon446-lab/proofspec) | Runtime Proof contract + JSON Schema for evidence bundles. |
| [**briefkit**](https://github.com/izon446-lab/briefkit) | Lint Orchestrator briefs against the 5 must-haves (goal, scope, done-when, constraints, proof). |
| [**sha-lock**](https://github.com/izon446-lab/sha-lock) | GitHub Action: fails the check unless evidence matches the PR head SHA. |
| [**skillforge**](https://github.com/izon446-lab/skillforge) | Scaffold Agent Skills packs with sane defaults and examples. |
| [**is-plain-obj**](https://github.com/izon446-lab/is-plain-obj) | Fork: check whether a value is a plain object. |
| [**is-empty-iterable**](https://github.com/izon446-lab/is-empty-iterable) | Fork: check whether an iterable is empty. |

## 🧭 Principles

- **L0 by default** — the smallest change that solves the problem; escalate scope only with reason.
- **Proof ≠ tests** — tests guard regressions; Proof shows the change actually works, at the exact head SHA.
- **No CloudAgent / LazyCodex writing lane** — those tools don't author code here; changes come through the reviewed OpenLane flow.
- **Public only** — everything we build is open, in public repos, under open licenses.

## 🤝 Contributing

1. Browse [good first issues](https://github.com/search?q=org%3Aizon446-lab+label%3A%22good+first+issue%22+state%3Aopen&type=issues) across the org.
2. Read [CONTRIBUTING.md](CONTRIBUTING.md) — short, we promise.
3. Open a small PR with Proof attached. One concern per PR.

Great starter areas: docs and examples in `proofspec`, new lint rules in `briefkit`, templates in `skillforge`.

## 📬 Contact / Owners

Maintained by [@izon446](https://github.com/izon446). Open an issue in the relevant repo, or mention @izon446.

## 📄 License

All projects are **MIT** licensed unless stated otherwise in the repo. Forks keep their upstream license.
