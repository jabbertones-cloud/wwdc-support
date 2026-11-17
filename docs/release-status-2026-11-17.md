# AppDev Atlas release and support status

_Last checked: November 17, 2026. Review after: December 1, 2026. Check the current listing and MCP source before repeating version or indexing claims._

## What is available

**AppDev Atlas** is an independent, read-only Apple-development research MCP. Its **45 research tools** search publicly available WWDC sessions (2020–2026), Apple documentation, HIG, Swift and Swift Evolution materials, and App Store guidance. It does not gain access to your App Store Connect account or GitHub write permissions.

- **Published ChatGPT plugin:** **v0.2.6**. [Open the AppDev Atlas listing](https://chatgpt.com/plugins/plugin_asdk_app_6ad90350c9fc8191abcbd6ccd10052c9).
- **Hosted MCP:** [wwdc-mcp.smatdesigns.com/mcp](https://wwdc-mcp.smatdesigns.com/mcp) for compatible remote MCP clients. Use the [source README](https://github.com/jabbertones-cloud/wwdc-mcp-server#readme) for client connection and authentication details.
- **Source and alternative packaging:** [wwdc-mcp-server](https://github.com/jabbertones-cloud/wwdc-mcp-server). Verify any MCPB/Registry version independently; a source commit does not change an installed client.

## What has changed in source but is not yet the published plugin

[PR #94](https://github.com/jabbertones-cloud/wwdc-mcp-server/pull/94) merged **v0.2.7 source metadata and two task-oriented skills**, `get-started` and `apple-app-research`; [PR #96](https://github.com/jabbertones-cloud/wwdc-mcp-server/pull/96) merged explicit skill pointers into both package manifests. That work **does not establish an OpenAI Platform upload, approval or public version upgrade**. Published v0.2.6 should remain the customer-facing version until separately confirmed.

The v0.2.7 work preserved **38 localization entries**, the existing logos and hosted MCP identity. [The proposed website link update, PR #95](https://github.com/jabbertones-cloud/wwdc-mcp-server/pull/95), is also separate from a website deployment.

A public listing can be reached directly while still being absent from an in-conversation plugin search. Support should not promise that a platform's recommendation or indexing algorithm will surface it.

## Help with a source or client problem

Use [troubleshooting](troubleshooting.md) and the [FAQ](faq.md) first, then [search public issues](https://github.com/jabbertones-cloud/wwdc-support/issues) or [file a sanitized report](https://github.com/jabbertones-cloud/wwdc-support/issues/new/choose). Include the MCP client, tool, safe query, expected result, actual result, and a link to the original public Apple source. Check `wwdc_ingest_status` or equivalent freshness evidence before interpreting an empty result as authoritative.

Do not post credentials, private code or unreleased Apple account information. AppDev Atlas is independent of Apple and OpenAI; its research results are source-backed guidance, not an Apple approval decision.

**Evidence:** [published/source version boundary](https://github.com/jabbertones-cloud/wwdc-mcp-server/pull/94); [merged skill pointer gate](https://github.com/jabbertones-cloud/wwdc-mcp-server/pull/96).
