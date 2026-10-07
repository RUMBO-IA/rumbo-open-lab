# RUMBO Open Lab

Public, explicitly open-source collaboration space for RUMBO experiments, prototypes, tools, examples, and community-driven ideas.

## Boundary

This repository is **not** the RUMBO production control plane and does not grant access to private Core repositories, customer data, production credentials, deployment systems, OpenAI projects, or other RUMBO services.

Do not commit:
- production secrets or credentials;
- customer or private business data;
- deploy keys or production environment configuration;
- private Core source copied from other RUMBO repositories;
- material you do not have the right to submit.

Untrusted community code must not run on RUMBO self-hosted runners.

## Contribution model

Community contribution is fork-first.

`FORK_PROPOSAL != REVIEWED != RIGHTS_CLEARED != ACCEPTED != MERGED != DEPLOYED != PRODUCTION_AUTHORIZED`

A pull request may be discussed or tested without being accepted.

All accepted contributions must comply with the Developer Certificate of Origin 1.1 and include a valid `Signed-off-by:` line as described in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

Unless otherwise stated for a specific third-party component, this repository is licensed under the Apache License 2.0. See [LICENSE](LICENSE).

The Apache-2.0 license for this repository does **not** apply to:
- `RUMBO-IA/Rumbo`;
- `RUMBO-IA/rumbo-control-queue`;
- `RUMBO-IA/rumbo-product-runtime`;
- `RUMBO-IA/rumbo-closed-lab`;
- customer/private data or unrelated RUMBO assets.

## Cost and compute

Default posture: `EXTERNAL_SPEND_USD=0`.

Prefer local development, contributor-owned compute, and included GitHub-hosted public-repository CI. Do not activate paid infrastructure, paid Codespaces sponsorship, marketplace products, or other metered resources without explicit authorization.

## Security

See [SECURITY.md](SECURITY.md). Do not place secrets or sensitive exploit details in public issues.
