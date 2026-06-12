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

<p align="center">
  <img src="https://img.shields.io/badge/Y%20Combinator-W24-orange" alt="Y Combinator W24" />
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

## Why Superagent?

AI is making vulnerability discovery cheap. Finding a flaw is becoming free. The cost didn't vanish — it moved.

Closing a vulnerability means proving it's real, reproducing it safely, writing a fix that doesn't break the build, and getting a human to merge it into main. A bad patch is worse than no patch. A fix that bumps a dependency and breaks the build, or a critical CVE that turns out not to apply to how you actually use the package, costs you more than the quiet bug you never touched.

The scanners detect and alert, hand you a report, and walk off. A report is a finding that never closed. The model labs are racing to commoditize the beep. The moat was never the model. When the finding is free, the only thing left worth owning is the close.

We don't care what model sits underneath. Best one this month, a different one next month. What we own is the pipeline: validate before anything reaches a person, ship a fix as a PR, get a human to approve and merge. The merge is the enforcement.

[Read the full thesis →](https://www.superagent.sh/blog/a-bad-patch-is-worse-than-no-patch)

---

## Core Ecosystem

### [superagent](https://github.com/superagent-ai/superagent) — Core SDK
![GitHub stars](https://img.shields.io/github/stars/superagent-ai/superagent?style=flat&label=%E2%98%85) ![GitHub forks](https://img.shields.io/github/forks/superagent-ai/superagent?style=flat)
- Detect and block prompt injections, redact PII and secrets, scan repos for threats. Embed safety directly into your app.

### [skills](https://github.com/superagent-ai/skills) — Security Skills
![GitHub stars](https://img.shields.io/github/stars/superagent-ai/skills?style=flat&label=%E2%98%85) ![GitHub forks](https://img.shields.io/github/forks/superagent-ai/skills?style=flat) ![License](https://img.shields.io/github/license/superagent-ai/skills)
- A collection of security skills for AI agents: vulnerability triage, infrastructure auditing, crypto hygiene, and more.

### [brin](https://github.com/superagent-ai/brin) — Context Trust Score
![GitHub stars](https://img.shields.io/github/stars/superagent-ai/brin?style=flat&label=%E2%98%85) ![GitHub forks](https://img.shields.io/github/forks/superagent-ai/brin?style=flat)
- Credit score for context. Measure what AI models miss without threat detection.

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
