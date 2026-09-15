# Security policy

## Reporting a vulnerability

Please report security problems privately, not in a public issue or pull request.

Use GitHub's private vulnerability reporting for this repository (you need to be signed in to GitHub):
https://github.com/tomevault-io/tomevault-plugin/security/advisories/new

Include what you found, how to reproduce it, and what you think the impact is. We will acknowledge the report, keep you updated while we investigate, and credit you in the fix unless you ask us not to.

## Scope

This repository is the TomeVault plugin. In scope: the plugin manifests, the MCP server they declare (`https://mcp.tomevault.io/`), and anything that could make an agent call an unexpected server, expose a credential, or act beyond what the user approved.

If the problem is in the TomeVault service at tomevault.io or mcp.tomevault.io rather than in this repository, report it the same way here and say so.

## Supported versions

Only the latest version is supported.
