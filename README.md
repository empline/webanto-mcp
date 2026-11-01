# Webanto MCP

Connect your AI assistant to a Webanto workspace to review product content, inspect SEO opportunities, and use organization knowledge.

## Install in Gemini CLI

```sh
gemini extensions install https://github.com/empline/webanto-mcp
```

Use `/mcp auth webanto` if sign-in is requested. The extension uses the hosted Streamable HTTP endpoint at `https://webanto.com/api/mcp`; OAuth discovery and dynamic client registration handle sign-in. No API key or client secret is bundled.

## What you can do

- Browse products synced to Webanto from Shopify and WooCommerce.
- Read a product and compare current content with copy proposals.
- Request a copy proposal and track the enrichment job.
- Inspect imported Google Search Console opportunities and data freshness.
- Retrieve brand guidance and uploaded organization knowledge.

Copy is created as a proposal for review. The MCP tools do not publish changes to a live store, place orders, or process payments.

## Walkthrough

[Watch the live MCP walkthrough](https://raw.githubusercontent.com/empline/webanto-mcp/main/assets/walkthrough.mp4). The recording uses the official MCP Inspector against the real endpoint and an isolated workspace with labelled sample data. It demonstrates the seven tools and the unsupported-action limits. Pauses are shortened; credentials are excluded.

![Sample product copy proposals in MCP Inspector](assets/screenshots/proposals.png)

## Requirements

You need a Webanto account and permission to connect the selected organization. The relevant store products, Search Console import, or organization knowledge must already exist in Webanto. Product enrichment requires an active subscription and available AI credits. Knowledge search consumes an embedding credit. OAuth scopes and your current organization permissions limit access on every call.

## Other clients

Use `https://webanto.com/api/mcp` in Claude or ChatGPT. The included `plugin.json` and `mcp.json` provide the OpenAI plugin package metadata; directory availability is subject to review.

## Links

[Setup documentation](https://webanto.com/ai/mcp) · [Support](https://webanto.com/contact) · [Privacy](https://webanto.com/privacy) · [Terms](https://webanto.com/terms)
