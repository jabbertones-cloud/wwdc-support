# WWDC MCP support

Report missing Apple sources, outdated results, incorrect citations or MCP connection problems.

**[Search issues](https://github.com/jabbertones-cloud/wwdc-support/issues)** · **[Report a bug](https://github.com/jabbertones-cloud/wwdc-support/issues/new/choose)** · **[Read agent instructions](AGENT-GITHUB-ISSUES.md)**

## Find an answer first

Search the [open and closed issues](https://github.com/jabbertones-cloud/wwdc-support/issues?q=is%3Aissue) for your symptom or MCP tool name. You may find a workaround without opening a new report.

- [Troubleshooting](docs/troubleshooting.md)
- [FAQ](docs/faq.md)

## Report a problem

1. Select **Report a bug** and choose the matching issue form.
2. Include the tool name, the query, MCP client and server version if known. For missing or stale results, include a public Apple source URL and the non-sensitive result of `wwdc_ingest_status`, if available.
3. Remove passwords, access tokens, customer information, private source code, screenshots with personal data and raw logs before posting.
4. Submit and keep the issue URL so you or your agent can check replies.

**Do not publish private or security information.** Use [private product support](https://wwdcmcp.smatdesigns.com/support) when the details cannot be shared publicly. Read [Security](SECURITY.md) before reporting a vulnerability.

## Use an AI agent to get help

An agent with a separately authorized GitHub connection can search issues, read the full discussion, prepare a safe report and, when requested, create an issue or post a reply. The maintained [GitHub MCP Server](https://github.com/github/github-mcp-server) exposes these issue operations. The product MCP does **not** automatically give the agent GitHub permissions.

Ask your agent: **"Check existing WWDC MCP support issues for this error and tell me whether there is a fix or workaround."**

To file a report, ask: **"Prepare a public bug report with safe details. Search for duplicates, then file it using my GitHub connection."**

If GitHub is not connected, your agent can prepare a report and give you the [new issue form](https://github.com/jabbertones-cloud/wwdc-support/issues/new/choose). It must not claim a ticket was created.

Read [Agent workflow](AGENTS.md) and [GitHub issue operations](AGENT-GITHUB-ISSUES.md).

## What happens next

You can track an issue and respond in its GitHub thread. A maintainer may ask for a minimal reproduction, share a workaround or request a new test. There is no guaranteed response time. A report is not fixed until the affected behavior has been independently checked.

WWDC MCP is independent and is not endorsed by Apple. It searches public developer material. It does not connect to private App Store Connect accounts or submit apps.

## Contribute

Corrections and reusable troubleshooting notes are welcome. See [Contributing](CONTRIBUTING.md) and [Support policy](SUPPORT.md).
