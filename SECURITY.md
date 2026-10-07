# Security Policy

RUMBO Open Lab is a public collaboration repository. It is not a production security boundary and must not contain production secrets, customer data, deploy credentials, or private Core material.

## Reporting a vulnerability

Do not publish sensitive exploit details, credentials, or personal/customer data in a public Issue.

If GitHub private vulnerability reporting or a private Security Advisory flow is available for this repository, use that private channel.

If no private reporting channel is available, open a minimal public Issue that says you need a private security contact channel, without including exploit details or sensitive data.

## Scope

A security report about this repository does not grant permission to test unrelated RUMBO systems, private repositories, customer systems, production infrastructure, or third-party services.

Only perform security testing on systems you own or are explicitly authorized to test.

## Secrets

If a secret is accidentally committed:
1. treat it as compromised;
2. do not merely delete it from the latest commit;
3. notify maintainers through a private channel;
4. rotate/revoke the affected credential in its source system.
