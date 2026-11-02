# Security Policy

## Reporting a vulnerability

Please **do not open a public issue** for security problems.

Report privately through GitHub: open the affected repository, go to **Security → Report a
vulnerability** and fill in the form. If that is not possible, email **sametbrr@gmail.com** with
the subject `SECURITY: <repository>`.

Please include:

- the affected repository and version (tag, npm/NuGet version or commit)
- steps to reproduce or a proof of concept
- the impact you expect

## What to expect

- Acknowledgement within **3 business days**
- A first assessment within **7 days**
- A fix or mitigation as soon as possible, released as a new version with a security advisory
- Credit in the advisory if you want it

## Supported versions

Security fixes go into the **latest release** of each project. Older versions are not patched;
please upgrade.

## Scope

Particularly relevant for these projects:

- secret handling and encryption (`crypt-sync`, `codeagent-sync`)
- MCP servers and API credentials (`openapi-rest-mcp`)
- agent plugins that run scripts or hooks on your machine
- release workflows and published packages (supply chain)
