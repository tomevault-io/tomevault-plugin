# TomeVault

Check AI instruction files, look up a company's record, keep a dated record of your own. Verification is free and needs no account.

## Install in Claude Code

```
/plugin marketplace add tomevault-io/tomevault-plugin
/plugin install tomevault@tomevault
```

The first call that needs your Vault opens a sign-in in your browser. Looking a
company up needs no account and never will.

## What it can do

Anyone, with no account: check a file against the Tome Standard, look up a
company's public record, verify a certificate, convert between formats.

Signed in: read your Vault, and save a corrected file back as a new version. The
previous version is always kept.

## What it can never do

Four things stay off the permission dial, whatever you set it to.

- Open a pull request in one of your repositories without you approving it first.
- Spend money, change your plan, or buy a seat.
- Change anyone's permissions, or create a credential.
- Delete anything from your record. It can add to it. It cannot erase it.

## This file is generated

Every manifest here is rendered from one source
(`src/lib/plugin/packaging/manifests.ts` in the TomeVault web repository) so
that the Claude, Agent Plugins and MCP registry manifests cannot drift apart.
Edit the source, re-run the generator, commit the diff.

Version 1.0.0 · https://tomevault.io/docs/mcp · oli@tomevault.io · [Privacy](https://tomevault.io/privacy)
