# AppDev Atlas Support

**AppDev Atlas** is an independent Apple-platform research MCP from **SMAT Designs**. It helps coding agents search and cite publicly available WWDC sessions, Apple Developer documentation, Human Interface Guidelines, Swift Evolution, API guidance, and sample code. AppDev Atlas is not affiliated with or endorsed by Apple or OpenAI.

This is the public support repository for AppDev Atlas. The legacy repository name `wwdc-support` and technical MCP identifiers are retained for compatibility; they are not the current product name.

**[Search support issues](https://github.com/jabbertones-cloud/wwdc-support/issues)** | **[Report a bug](https://github.com/jabbertones-cloud/wwdc-support/issues/new/choose)** | **[Support website](https://wwdcmcp.smatdesigns.com/support)** | **[Agent issue workflow](AGENT-GITHUB-ISSUES.md)**

## Product and documentation

- [AppDev Atlas website](https://wwdcmcp.smatdesigns.com/): capabilities, independent-service information, and support
- [Hosted MCP endpoint](https://wwdc-mcp.smatdesigns.com/mcp): backward-compatible remote MCP URL
- [Open-source server](https://github.com/jabbertones-cloud/wwdc-mcp-server): implementation, client setup, and tests
- [Main README](https://github.com/jabbertones-cloud/wwdc-mcp-server#readme): installation, technical IDs, and source coverage
- [FAQ](docs/faq.md) and [troubleshooting](docs/troubleshooting.md): help with connections and results

AppDev Atlas exposes **45 read-only research tools**. Its Apple-platform sources include WWDC 2020 through 2026, HIG, Swift language and evolution guidance, Apple documentation, and App Store Review Guidelines. These are indexed public sources, not private Apple account access. Check corpus freshness and the original source when accuracy matters.

## Find an answer first

Search [open and closed issues](https://github.com/jabbertones-cloud/wwdc-support/issues?q=is%3Aissue) using your error message, tool name, or source URL. Read the [FAQ](docs/faq.md) and [troubleshooting guide](docs/troubleshooting.md) before filing duplicates.

## Report a problem or request a feature

1. Open the [issue form](https://github.com/jabbertones-cloud/wwdc-support/issues/new/choose) and choose a bug report or feature request.
2. Describe what you expected, what happened, how to reproduce it, the MCP client, and the relevant tool and version. For missing or outdated content, link to the public developer.apple.com source.
3. Remove passwords, tokens, private source code, personal details, Apple account records, and raw logs before submitting.
4. Save the issue URL to follow maintainer responses. A merged PR does not guarantee a live fix.

You can read public issues without a GitHub sign-in. Creating or replying to issues requires **your own authorized GitHub account**; AppDev Atlas never supplies or embeds a shared GitHub owner token.

For sensitive requests and possible vulnerabilities, use [private product support](https://wwdcmcp.smatdesigns.com/support) and follow the [security policy](SECURITY.md). Do not post sensitive information in a public issue.

## AI agent support

With a separately connected, authorized GitHub MCP or connector, an agent can search, read, draft, create, and reply to support issues. It must check for duplicates, sanitize submissions, and obtain authorization before publishing. The product's 45 research tools do not grant GitHub write access.

Follow [AGENTS.md](AGENTS.md) and [GitHub Issue Operations](AGENT-GITHUB-ISSUES.md). Keep the issue tracker reserved for genuine user reports, not artificial test tickets.
