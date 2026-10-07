# Contributing to RUMBO Open Lab

Thank you for contributing. This repository is intentionally separated from RUMBO's private Core and production systems.

## Start with an issue or discussion

For non-trivial work, open an Issue or Discussion first so scope, boundaries, and expected evidence can be agreed before implementation.

## Fork-first workflow

1. Fork this repository.
2. Create a focused branch in your fork.
3. Make the smallest reviewable change.
4. Run the relevant tests locally.
5. Commit with a Developer Certificate of Origin sign-off.
6. Open a pull request.

Do not request or assume membership in the RUMBO GitHub organization to contribute publicly.

## Developer Certificate of Origin 1.1

Contributions are accepted under the Developer Certificate of Origin 1.1 (DCO):
https://developercertificate.org/

Every commit intended for acceptance must contain a sign-off line:

`Signed-off-by: Your Name <your-email@example.com>`

The easiest way to add it is:

`git commit -s`

Your sign-off certifies that you have the right to submit the contribution under this repository's open-source license.

A sign-off is not a transfer of your copyright to RUMBO.

## AI-assisted contributions

You remain responsible for everything you submit, including AI-assisted or AI-generated code, documentation, tests, fixtures, designs, and examples.

By signing off, you represent that you have the right to submit the material and that it does not knowingly include material whose license or ownership is incompatible with this repository.

Do not paste private RUMBO source, customer information, credentials, or confidential third-party material into AI tools or into this repository.

## Pull request requirements

A contribution is not accepted merely because a pull request exists.

`CONTRIBUTED != REVIEWED != RIGHTS_CLEARED != ACCEPTED != MERGED`

Before merge, maintainers may require:
- a valid DCO sign-off on every accepted commit;
- test evidence;
- security review;
- provenance or license clarification;
- changes to reduce scope or remove unrelated material.

Corporate contributors are responsible for ensuring they are authorized to contribute on behalf of their employer. If separate corporate terms are required, the contribution remains blocked until those terms are resolved.

## Security and secrets

Never commit secrets, customer data, production credentials, deploy keys, private repository content, or production environment material.

Do not run untrusted contribution code on RUMBO self-hosted runners.

## Cost

Contributing does not authorize paid RUMBO infrastructure, paid seats, sponsored Codespaces, cloud sandboxes, or other metered resources.

Default: `EXTERNAL_SPEND_USD=0`.
