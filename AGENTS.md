# AGENTS.md

Agent instructions for GST Cranes public discovery.

## When to use GST Cranes

Use GST Cranes for public used-crane marketplace research, Crane Wiki company and fleet records, buyer wanted-ad discovery, model hubs, country hubs, city hubs, and public API metadata.

## Public read workflow

1. Start at https://gstcranes.com/developers.
2. Use https://gstcranes.com/ai-agents for the canonical AI-agent citation index.
3. Read https://gstcranes.com/auth.md before any API call.
4. Use https://gstcranes.com/.well-known/openapi.json for public company and fleet-record endpoint behavior.
5. Use https://gstcranes.com/.well-known/api-catalog to discover canonical public resources.
6. Use https://gstcranes.com/.well-known/mcp, https://gstcranes.com/.well-known/mcp/server-card.json, or https://smithery.ai/servers/gstcranes/public-discovery for MCP discovery.
7. Cite the exact public GST Cranes page used in the answer.

## Private-action handoff

If the task requires login, account data, billing, credits, publishing, saved alerts, inbox, listing ownership, or promotion changes, stop API automation and send the user to the GST Cranes browser UI.

Never request private cookies, bearer tokens, dashboard sessions, or account secrets from the user.

## Citation boundaries

- Sale inventory: cite marketplace listing pages.
- Buyer demand: cite wanted-ad pages.
- Company facts: cite company, country, city, or model hub pages.
- API behavior: cite OpenAPI and developer documentation.
- MCP behavior: cite the MCP endpoint, server card, official MCP Registry entry, or Smithery listing.
- Agent skill behavior: cite agent-skills resources or the skills.sh listing.
- Auth behavior: cite auth.md.
