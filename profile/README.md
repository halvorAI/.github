# HalvorAI

**We prove what your AI agents spent, on every rail, and hand your bank the evidence.**

HalvorAI records every payment an AI agent makes as a signed, attributed event. Each event names the agent, the owner it acted for, the instruction it followed, and the network proof that came with the payment. We verify those proofs, screen every payee, watch each agent for unusual behavior, and produce evidence packs a sponsor bank can check offline without trusting us.

HalvorAI works after authorization. It is not in the payment path, so it never slows or blocks a payment.

## Open source

| Repository | What it is | Status |
| --- | --- | --- |
| [`ape-schema`](https://github.com/halvorAI/ape-schema) | Agent Payment Event (APE) v0.1: an open, rail-neutral JSON Schema for agent payments, with examples, conformance tests and mappings to AP2 mandates, Verifiable Intent, Visa TAP and x402 | Active, contributions welcome |
| [`agent-fraud-taxonomy`](https://github.com/halvorAI/agent-fraud-taxonomy) | Agent payment fraud taxonomy v0.1: six patterns (runaway loop, scope drift, prompt injection, payee swap, agent impersonation, mandate splitting), each mapped to the APE fields that reveal it | Active, contributions welcome |
| [`ingest-js`](https://github.com/halvorAI/ingest-js) | `@halvorai/ingest`: TypeScript SDK and CLI. Signs and sends events from Stripe, x402, MPP and MCP payment tools, validates events offline, and verifies evidence packs | Active, contributions welcome |
| [`ingest-python`](https://github.com/halvorAI/ingest-python) | `halvorai-ingest`: Python SDK. Signs and sends events with agent attribution, works offline with your own sink, and observes x402 payments | Active, contributions welcome |
| [`ingest-go`](https://github.com/halvorAI/ingest-go), [`ingest-java`](https://github.com/halvorAI/ingest-java) | Go and Java/Kotlin SDKs | Frozen since 17 Nov 2026: still published, no new features. Use `ingest-js` or `ingest-python` for new integrations |

All code here is Apache-2.0 unless a repository says otherwise.

## Start contributing

You don't need an account, an API key or access to anything private. Every active repository runs its tests offline.

- **Starter tasks:** [`good first issue`](https://github.com/search?q=org%3AhalvorAI+label%3A%22good+first+issue%22+state%3Aopen&type=issues) and [`help wanted`](https://github.com/search?q=org%3AhalvorAI+label%3A%22help+wanted%22+state%3Aopen&type=issues) across the four active repositories.
- **Building agent payments, an agent wallet or a Know Your Agent product?** Propose the fields or mapping your rail needs on [`ape-schema`](https://github.com/halvorAI/ape-schema/issues). We want the schema to be shared, not ours.
- **Seen an agent payment failure that isn't in the taxonomy?** Open an issue on [`agent-fraud-taxonomy`](https://github.com/halvorAI/agent-fraud-taxonomy/issues). We credit accepted additions.

Each repository has a `CONTRIBUTING.md` with setup commands. We acknowledge new issues within 1 business day and give pull requests a first review within 3.

## Rails

Stripe and Stripe Issuing · x402 · MPP · MCP payment tools · cards (Visa and Mastercard agent tokens) · stablecoins and bank transfers next

## Get started

- **Docs:** [docs.halvorai.com](https://docs.halvorai.com)
- **Quickstart:** [Send your first event](https://docs.halvorai.com/get-started/quickstart/)
- **Event schema:** [APE v0.1 reference](https://docs.halvorai.com/schema/)
- **Early access:** [halvorai.com](https://halvorai.com/?utm_source=github&utm_campaign=org_profile#early-access)

## Security

Please report vulnerabilities privately to **hello@halvorai.com**, not in public issues.

---

[Website](https://halvorai.com) · [Docs](https://docs.halvorai.com) · [LinkedIn](https://www.linkedin.com/company/halvorai) · hello@halvorai.com
