# HalvorAI

**We prove what your AI agents spent, on every rail, and hand your bank the evidence.**

<p align="center"><picture><source media="(min-width: 1012px)" srcset="https://raw.githubusercontent.com/halvorAI/ape-schema/main/assets/figures/hero-wide.svg"><img src="https://raw.githubusercontent.com/halvorAI/ape-schema/main/assets/figures/hero-narrow.svg" alt="An AI agent pays a merchant over a payment rail such as Stripe, a card, x402 or MPP. HalvorAI is not on that path. Beside it, the HalvorAI SDK observes the payment read-only and records a signed event, events are assembled into a signed evidence pack, and the bank verifies the pack offline."></picture></p>

HalvorAI records every payment an AI agent makes as a signed, attributed event: which agent paid, for which owner, on which instruction, with the network proof that came with the payment. We verify those proofs, screen every payee, watch each agent for unusual behavior, and produce evidence packs a sponsor bank can check offline without trusting us.

HalvorAI records and proves agent payments after the fact. It is never in the payment path and cannot slow or block a payment.

It's for teams building agent wallets, agent cards and agentic checkout, and for the risk and compliance teams at the banks behind them.

## Choose a tool

| I want to | Repository | Install |
| --- | --- | --- |
| Record signed agent payment events from Node.js (Stripe, x402, MPP, MCP) and verify evidence packs | [`ingest-js`](https://github.com/halvorAI/ingest-js) | `npm install @halvorai/ingest` <br> <a href="https://www.npmjs.com/package/@halvorai/ingest"><img height="16" alt="npm" src="https://img.shields.io/npm/v/@halvorai/ingest?style=flat-square&label=npm&color=4A6100"></a> |
| Record signed agent payment events from Python (Stripe, x402) | [`ingest-python`](https://github.com/halvorAI/ingest-python) | `pip install halvorai-ingest` <br> <a href="https://pypi.org/project/halvorai-ingest/"><img height="16" alt="PyPI" src="https://img.shields.io/pypi/v/halvorai-ingest?style=flat-square&label=pypi&color=4A6100"></a> |
| Describe an agent payment in one open, rail-neutral format, mapped to AP2, Verifiable Intent, Visa TAP and x402 | [`ape-schema`](https://github.com/halvorAI/ape-schema) | [`schema.halvorai.com/ape/v0.1.json`](https://schema.halvorai.com/ape/v0.1.json) <br> <img height="16" alt="APE v0.1" src="https://img.shields.io/badge/APE-v0.1-C6F432?style=flat-square&labelColor=1C1C1C"> |
| Name and detect the ways agent payments go wrong: runaway loops, scope drift, prompt injection, payee swap, impersonation, mandate splitting | [`agent-fraud-taxonomy`](https://github.com/halvorAI/agent-fraud-taxonomy) | [`taxonomy.json`](https://github.com/halvorAI/agent-fraud-taxonomy/blob/main/taxonomy.json) |
| Keep using an existing Go or Java/Kotlin integration | [`ingest-go`](https://github.com/halvorAI/ingest-go), [`ingest-java`](https://github.com/halvorAI/ingest-java) | <img height="16" alt="status: frozen" src="https://img.shields.io/badge/status-frozen-7A766C?style=flat-square"> no new features since 17 Nov 2026 |

All code here is Apache-2.0 unless a repository says otherwise.

## Start contributing

You don't need an account, an API key or access to anything private. Every active repository runs its tests offline.

| I want to | Go to |
| --- | --- |
| Pick up a starter task | [`good first issue`](https://github.com/search?q=org%3AhalvorAI+label%3A%22good+first+issue%22+state%3Aopen&type=issues) and [`help wanted`](https://github.com/search?q=org%3AhalvorAI+label%3A%22help+wanted%22+state%3Aopen&type=issues) |
| Propose fields or a mapping for my rail, agent wallet or Know Your Agent product | [`ape-schema` issues](https://github.com/halvorAI/ape-schema/issues). We want the schema to be shared, not ours. |
| Report an agent payment failure that isn't in the taxonomy | [`agent-fraud-taxonomy` issues](https://github.com/halvorAI/agent-fraud-taxonomy/issues). We credit accepted additions. |

Each repository has a `CONTRIBUTING.md` with setup commands. We acknowledge new issues within 1 business day and give pull requests a first review within 3.

## Rails

`Stripe` · `Stripe Issuing` · `x402` · `MPP` · `MCP payment tools` · `Visa and Mastercard agent tokens` · next: stablecoins and bank transfers

## Read more

| I want to | Read |
| --- | --- |
| Send my first event | [Quickstart](https://docs.halvorai.com/get-started/quickstart/) |
| Look up an event field | [APE v0.1 reference](https://docs.halvorai.com/schema/) |
| Read all the docs | [docs.halvorai.com](https://docs.halvorai.com) |
| Get a sandbox API key | [Early access](https://halvorai.com/?utm_source=github&utm_campaign=org_profile#early-access) |

## Security

Please report vulnerabilities privately to **hello@halvorai.com**, not in public issues.

---

[Website](https://halvorai.com) · [Docs](https://docs.halvorai.com) · [LinkedIn](https://www.linkedin.com/company/halvorai) · hello@halvorai.com
