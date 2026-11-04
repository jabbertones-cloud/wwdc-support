# WWDC MCP support

Public support for the read-only WWDC, Apple documentation, Swift and App Review research MCP.

**[Browse and search issues](https://github.com/jabbertones-cloud/wwdc-support/issues)** | **[Report a bug](https://github.com/jabbertones-cloud/wwdc-support/issues/new/choose)**

This is the public support and bug-tracking repository. It intentionally contains no application source and starts with **zero issues**. It holds a README, agent instructions and issue templates. The product source remains in its existing repository.

## Request help

Before reporting, search open and closed issues for the symptom or MCP tool name. Include a plain-language summary, expected and observed behavior, sanitized steps to reproduce, relevant MCP client and version, and whether the problem is repeatable. Use the issue form for bugs and feature requests.

## Support through an AI agent

An agent can use [GitHub's official MCP server](https://github.com/github/github-mcp-server) or the user's authenticated GitHub CLI to search and read issues, file a report when the user asks, and reply to existing issues. Read [AGENTS.md](AGENTS.md) for the exact workflow. The WWDC MCP MCP does **not** embed an owner GitHub token and does not grant agents GitHub access automatically.

If GitHub is not connected, the agent must prepare a redacted issue title and body with a link to the new-issue form, not claim it created an issue.

## Public safety

Never post Apple credentials, private code, unpublished App Store Connect records, account identifiers, device IDs, access tokens, or customer data. For suspected security vulnerabilities, use a private disclosure channel, not a public issue.

WWDC MCP is an independent community project, not Apple. Support responses cannot modify App Store Connect and must distinguish corpus freshness from official current platform state.

## Project

- Product source: `jabbertones-cloud/wwdc-mcp-server` (the source repository may have different visibility)
- Issue tracker: https://github.com/jabbertones-cloud/wwdc-support/issues
