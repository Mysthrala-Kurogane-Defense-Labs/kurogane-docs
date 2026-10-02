# Kurogane Docs

Practical industrial cybersecurity preparation for **small businesses and technical teams**. These guides help produce an inventory, access review, decision record and evidence checklist. They work without installing Kurogane Hub.

## Choose a starting point

| Reader / task | Start here | Output |
| --- | --- | --- |
| Company owner or operations lead | [First preparation session](docs/sme-onboarding.md) | Bounded scope, owners and three priorities |
| Technician building an inventory | [Plant modeling](docs/plant-modeling.md) | Asset and dependency register |
| Team reviewing a provider | [Deployment choices](docs/deployment-models.md) | Responsibility and evidence table |
| Developer evaluating examples | [Satellite boundary](docs/satellite-architecture.md) | Public contract and unanswered integration decisions |
| Buyer checking requirements | [NIS2](docs/nis2-alignment.md), [METI](docs/meti-alignment.md) | Applicability questions and source register |

## Guides

- Deployment: [on-premise](docs/on-premise-deployment.md), [hybrid](docs/hybrid-deployment.md).
- Information and risk: [data location and control](docs/data-sovereignty.md), [operational risk](docs/operational-risk.md).
- Modeling: [plant inventory](docs/plant-modeling.md), [digital twin terminology](docs/digital-twin-overview.md).
- Definitions and scope: [glossary](docs/glossary.md), [FAQ](docs/faq.md), [primary references](docs/references.md).
- Executable examples: [SDK](https://github.com/Mysthrala-Kurogane-Defense-Labs/kurogane-satellite-sdk) and [synthetic Labs](https://github.com/Mysthrala-Kurogane-Defense-Labs/kurogane-labs).
- Provider review: [security questions and evidence](https://github.com/Mysthrala-Kurogane-Defense-Labs/kurogane-security-model).

## Evidence and limits

Each guide separates recommended actions from evidence of implementation. Record an owner, date and scope for each result; mark unknowns instead of assuming a control exists. Deployment pages are planning guides, not instructions to install the private Hub. The public SDK has no HTTP transport, and the labs use invented data.

Regulatory references do not establish applicability or certify compliance. Review the relevant jurisdiction, current law and contractual requirements with qualified reviewers. A source's presence is not evidence of a deployed control.

## Corrections and license

Open an issue with the page, disputed claim, authoritative source and checked date. Use synthetic examples and keep customer evidence private. Documentation remains CC BY-ND 4.0; explicitly marked code snippets are Apache-2.0. See [license](LICENSE.md).
