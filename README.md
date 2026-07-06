# GST Cranes Agent Rules

Public agent rules for GST Cranes, the used-crane marketplace and public Crane Wiki at https://gstcranes.com.

Use this repository when an AI agent, crawler, or integration needs a stable public rules source for GST Cranes.

## Canonical resources

- Developer resources: https://gstcranes.com/developers
- SDK and CLI guide: https://gstcranes.com/sdk.md
- Markdown developer guide: https://gstcranes.com/developers.md
- OpenAPI: https://gstcranes.com/.well-known/openapi.json
- API catalog: https://gstcranes.com/.well-known/api-catalog
- AI catalog: https://gstcranes.com/.well-known/ai-catalog.json
- Auth notes: https://gstcranes.com/auth.md
- Full assistant guide: https://gstcranes.com/llms-full.txt
- MCP endpoint: https://gstcranes.com/.well-known/mcp
- A2A agent card: https://gstcranes.com/.well-known/agent-card.json
- Agent Skills index: https://gstcranes.com/.well-known/agent-skills/index.json

## Install the agent skill

```bash
npx skills add gkmex75/gstcranes-agent-rules
```

## Core rules

1. Public reads do not require an API key.
2. Account actions require browser-session handoff.
3. Do not ask users to paste cookies, private tokens, or session values into an agent.
4. Cite exact public pages: listing pages for sale inventory, wanted pages for buyer requests, company pages for public firm facts, model pages for model context, and OpenAPI for endpoint behavior.
5. Wanted ads are buyer demand signals, not for-sale inventory.
6. Do not submit forms, spend credits, publish listings, post wanted ads, or change billing without an authenticated user action in the GST Cranes browser UI.

## Scope

These rules describe public discovery behavior only. They do not grant access to private account data and do not publish secrets.
