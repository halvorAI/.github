# HalvorAI

**We prove what your AI agents spent, on every rail, and hand your bank the evidence.**

HalvorAI records every payment an AI agent makes as a signed, attributed event. Each event names the agent, the owner it acted for, the instruction it followed, and the network proof that came with the payment. We verify those proofs, screen every payee, watch each agent for unusual behavior, and produce evidence packs a sponsor bank can check offline without trusting us.

HalvorAI works after authorization. It is not in the payment path, so it never slows or blocks a payment.

## Open source

| Repository | What it is | Status |
| --- | --- | --- |
| [`ape-schema`](https://github.com/halvorai/ape-schema) | Agent Payment Event (APE) v0.1: an open, rail-neutral JSON Schema for agent payments, with examples and mappings to AP2 mandates, Verifiable Intent, Visa TAP and x402 | Live |
| [`ingest-js`](https://github.com/halvorai/ingest-js) | `@halvorai/ingest`: TypeScript SDK and CLI. Signs and sends events from Stripe, x402, MPP and MCP payment tools, validates events offline, and verifies evidence packs | Live |
| [`ingest-python`](https://github.com/halvorai/ingest-python) | `halvorai-ingest`: Python SDK. Signs and sends events with agent attribution, works offline with your own sink, and observes x402 payments | Live |
| [`agent-fraud-taxonomy`](https://github.com/halvorai/agent-fraud-taxonomy) | Agent payment fraud taxonomy v0.1: six patterns (runaway loop, scope drift, prompt injection, payee swap, agent impersonation, mandate splitting), each mapped to the APE fields that reveal it | Live |

All code here is Apache-2.0 unless a repository says otherwise.

## Rails

Stripe and Stripe Issuing · x402 · MPP · MCP payment tools · cards (Visa and Mastercard agent tokens) · stablecoins and bank transfers next

## Get started

- **Docs:** [docs.halvorai.com](https://docs.halvorai.com)
- **Quickstart:** [Send your first event](https://docs.halvorai.com/get-started/quickstart/)
- **Event schema:** [APE v0.1 reference](https://docs.halvorai.com/schema/)
- **Early access:** [halvorai.com](https://halvorai.com/?utm_source=github&utm_campaign=org_profile#early-access)

## Contributing

We'd like the event schema to be shared, not ours. If you build agent payments, an agent wallet or a Know Your Agent product, open an issue on `ape-schema` with the fields your rail needs. Seen an agent payment failure that isn't in the taxonomy? Open an issue on `agent-fraud-taxonomy`; we credit accepted additions.

## Security

Please report vulnerabilities privately to **hello@halvorai.com**, not in public issues.

---

[Website](https://halvorai.com) · [Docs](https://docs.halvorai.com) · [LinkedIn](https://www.linkedin.com/company/halvorai) · hello@halvorai.com
