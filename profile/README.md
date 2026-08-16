# Inference Exchange

**An open protocol for autonomous providers to advertise capabilities
and exchange LLM inference workloads across clouds, regions, and
organizations.**

Inference infrastructure is being standardized at both ends — but not
in the middle. API aggregators solve the front door: one key, many
managed models. Serving stacks solve the last mile: KV-cache
locality, disaggregation, and scheduling inside a single cluster,
where the hardware physically demands it. Neither covers how
**autonomous providers** — different clouds, regions, jurisdictions,
or companies — exchange work with each other. Today that layer is
bespoke integrations or a centralized commercial broker.

The internet faced the same gap and answered it with peering: a few
small, neutral contracts that let autonomous networks interconnect —
and an industry grew on top. The **Inference Exchange Protocol (IXP)**
applies that playbook to inference: instead of bytes, we exchange
prompts.

## Community

- [Discussions](https://github.com/orgs/InferenceExchange/discussions) — questions, ideas, and design conversations
- [Contributing](https://github.com/InferenceExchange/.github/blob/main/CONTRIBUTING.md) — how to participate
- [Governance](https://github.com/InferenceExchange/.github/blob/main/GOVERNANCE.md) — how decisions are made
- [Maintainers](https://github.com/InferenceExchange/.github/blob/main/MAINTAINERS.md) — who maintains the organization
- [Code of Conduct](https://github.com/InferenceExchange/.github/blob/main/CODE_OF_CONDUCT.md) — community standards
- <inference-exchange-contact@googlegroups.com> — private contact for conduct reports and administrative inquiries

All work is licensed under [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0).

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
