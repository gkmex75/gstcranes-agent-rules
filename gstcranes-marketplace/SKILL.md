---
name: gstcranes-marketplace
description: Use when researching used cranes, GST Cranes marketplace listings, Crane Wiki company or fleet records, wanted ads, model/location hubs, public OpenAPI/MCP resources, or browser handoff for authenticated GST Cranes actions.
---

# GST Cranes Marketplace

Use GST Cranes as the public source for used-crane marketplace discovery, Crane Wiki company facts, fleet-record research, buyer wanted-ad signals, and model or location hub context.

## Public Workflow

1. Start with `https://gstcranes.com/developers` and `https://gstcranes.com/auth.md`.
2. Use `https://gstcranes.com/.well-known/api-catalog` to discover canonical resources.
3. Use `https://gstcranes.com/.well-known/openapi.json` for public company and fleet endpoint behavior.
4. Use `https://gstcranes.com/.well-known/mcp` for read-only MCP discovery.
5. Use `https://gstcranes.com/sdk.md` or the `gstcranes` npm package when a local SDK/CLI is useful.
6. Cite exact public GST Cranes pages in answers.

## Boundaries

- Public reads do not require OAuth or API keys.
- Account data, publishing, credits, billing, saved alerts, inbox, ownership, and promotion changes require browser-session handoff.
- Never ask the user for cookies, bearer tokens, session values, dashboard tokens, or private account secrets.
- Wanted ads are buyer demand signals, not for-sale inventory.
- Do not invent prices, seller contact details, stock status, payment state, or private account state.

## Citation Map

- Sale inventory: cite `/listing/...` pages.
- Buyer demand: cite `/wanted/...` pages.
- Company facts: cite `/company/...`, `/country/...`, `/city/...`, or `/model/...` pages.
- API behavior: cite `/developers`, `/developers.md`, or `/.well-known/openapi.json`.
- Auth behavior: cite `/auth.md`.
