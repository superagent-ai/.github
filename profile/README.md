<p align="center">
  <img src="logo.png" width="80" alt="Superagent" />
</p>

<h1 align="center">Superagent</h1>

<p align="center">
  <strong>An AI security team that finds, patches, and discloses vulnerabilities.</strong><br/>
  Every fix ships as a PR — remediation in hours, not months.
</p>

<p align="center">
  <a href="https://superagent.sh">Website</a> ·
  <a href="https://docs.superagent.sh">Docs</a> ·
  <a href="https://discord.gg/spZ7MnqFT4">Discord</a> ·
  <a href="https://huggingface.co/superagent-ai">HuggingFace</a>
</p>

---

## Overview

Superagent is an AI security engine for code and agents. Find vulnerabilities across your repos, validate exploit paths, and ship fixes your team approves — all inside your existing GitHub workflow.

The platform follows a simple workflow:

> **Find → Validate → Fix → Disclose**

---

## What Superagent Does

One engine, one GitHub-native workflow, one output: a pull request with a validated fix.

| Capability | Job |
| --- | --- |
| **Find** | Continuous adversarial research across repos and agents. Chains findings the way a real attacker builds a kill chain — finding what static scanners miss. |
| **Patch** | Every validated fix ships as a PR your team approves. No new dashboard, no context switching off GitHub. |
| **Triage** | Deduplicates and prioritizes incoming vulnerability reports. Surfaces real exploit paths from noise automatically. |
| **Scan** | PR scanning runs on every pull request so security issues are caught before code merges. |
| **Disclose** | Coordinated disclosure with severity tracking, embargo timelines, and advisory publishing. |
| **Trust** | Contributor trust scores and CLA checks on every PR. Outside contributors sign once, maintainers stay compliant. |

---

## Built for Production

- **Humans in the loop:** Agents do the research. Your team approves every fix before it ships.
- **GitHub native:** Install apps and meet your team where they already work. Findings land as check runs and PR comments.
- **Free for open source:** Public repos get full vulnerability finding, patching, and disclosure at no cost.
- **10× security work without adding headcount:** Run end-to-end security workflows on private repos and agents with the team you already have.

---

## Core Ecosystem

### [superagent](https://github.com/superagent-ai/superagent) — Core SDK
- **Stars:** ~6.6k | **Forks:** ~959 | **Language:** TypeScript
- Detect and block prompt injections, redact PII and secrets, scan repos for threats. Embed safety directly into your app.

### [superagent-github](https://github.com/superagent-ai/superagent-github) — GitHub App
- **Stars:** 4 | **Language:** TypeScript
- Automatically scans pull requests for security threats and evaluates contributor trust profiles.

### [open-cla](https://github.com/superagent-ai/open-cla) — Open CLA Platform
- **Language:** TypeScript
- GitHub App PR checks, PDF templates, and e-sign for contributor license agreements.

### [skills](https://github.com/superagent-ai/skills) — Security Skills
- **Stars:** 68 | **Forks:** 9 | **License:** MIT | **Language:** Python
- A collection of security skills for AI agents: vulnerability triage, infrastructure auditing, crypto hygiene, and more.

### [vibekit](https://github.com/superagent-ai/vibekit) — Agent Sandbox
- **Stars:** ~1.8k | **Forks:** ~233 | **Language:** TypeScript
- Run coding agents in isolated sandboxes with data redaction and observability.

### [reag](https://github.com/superagent-ai/reag) — Reasoning Augmented Generation
- **Stars:** 902 | **Forks:** 59 | **Language:** Python
- Query documents with full context, not chunked embeddings.

### [grok-cli](https://github.com/superagent-ai/grok-cli) — Coding Agent
- **Stars:** ~3.2k | **Forks:** ~390 | **Language:** TypeScript
- An open-source coding agent for the Grok API.

### [brin](https://github.com/superagent-ai/brin) — Context Trust Score
- **Stars:** 44 | **Forks:** 8 | **Language:** Shell
- Credit score for context. Measure what AI models miss without threat detection.

---

## Notable Repositories

| Repository | Stars | Language | Description |
|---|---|---|---|
| [superagent](https://github.com/superagent-ai/superagent) | ~6.6k | TypeScript | Detect/block prompt injections, redact PII/secrets, scan repos for threats. |
| [grok-cli](https://github.com/superagent-ai/grok-cli) | ~3.2k | TypeScript | Open-source coding agent for the Grok API. |
| [vibekit](https://github.com/superagent-ai/vibekit) | ~1.8k | TypeScript | Run coding agents in isolated sandboxes with redaction and observability. |
| [reag](https://github.com/superagent-ai/reag) | 902 | Python | Reasoning Augmented Generation. Query documents with full context. |
| [skills](https://github.com/superagent-ai/skills) | 68 | Python | Collection of security skills for AI agents. |
| [brin](https://github.com/superagent-ai/brin) | 44 | Shell | Credit score for context. |
| [open-cla](https://github.com/superagent-ai/open-cla) | — | TypeScript | Open-source CLA platform with GitHub App PR checks and e-sign. |
| [superagent-github](https://github.com/superagent-ai/superagent-github) | 4 | TypeScript | GitHub App that scans PRs for security threats and evaluates contributor trust. |

*Organization total: 24 repositories. Top languages: TypeScript, Python, JavaScript, Rust, Shell.*

---

## Who Builds with Superagent

- **Open source maintainers:** Shipping free security for public repos. Vulnerability finding, patching, and disclosure with no manual overhead.
- **AI agent builders:** Adding guardrails to production agents. Blocking prompt injections, redacting sensitive data, and sandboxing coding agents.
- **Enterprise security teams:** Running continuous find-and-fix on private repos and agents. 10× the security output without expanding headcount.

---

## Resources & Links

- **Website:** [superagent.sh](https://superagent.sh)
- **Docs:** [docs.superagent.sh](https://docs.superagent.sh)
- **Blog:** [superagent.sh/blog](https://superagent.sh/blog)
- **Discord:** [discord.gg/spZ7MnqFT4](https://discord.gg/spZ7MnqFT4)
- **X/Twitter:** [x.com/superagent_ai](https://x.com/superagent_ai)
- **HuggingFace:** [huggingface.co/superagent-ai](https://huggingface.co/superagent-ai)

---

<p align="center">
  <img src="https://img.shields.io/badge/Y%20Combinator-W24-orange" alt="Y Combinator W24" />
</p>
